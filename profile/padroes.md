# 🚀 Guia de Boas Práticas da Autocom3

Este documento é a fonte de verdade para os padrões de desenvolvimento na Autocom3, garantindo que nossos projetos sejam consistentes, manuteníveis e de alta qualidade.

---

## ✨ Código Limpo (Clean Code)

Um código limpo pode ser lido e aprimorado por qualquer desenvolvedor(a).

- **Nomes Claros e Significativos:** Variáveis, funções e classes devem expressar sua intenção. Evite abreviações e nomes genéricos.
- **Funções Pequenas e Focadas:** Cada função deve fazer apenas uma coisa e fazê-la bem.
- **DRY (Don't Repeat Yourself):** Centralize lógicas comuns em funções reutilizáveis para evitar duplicação.
- **Comentários Úteis:** Comente o **porquê** de uma implementação complexa, não o *como*. O código deve autoexplicar o *como*.
- **Tratamento de Erros:** Exceções devem ser tratadas de forma explícita e informativa. Evite blocos `try/catch` vazios.
- **Consistência:** Siga sempre as convenções de formatação e arquitetura já estabelecidas no projeto.

> **Dica de Ouro:** Leia seu código em voz alta. Se for difícil de explicar, ele provavelmente precisa ser simplificado.

---

## 🌿 Controle de Versão com Git

Um histórico de commits bem organizado é fundamental para a saúde do projeto.

### Padrão de Commits (Conventional Commits)
Adotamos o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/) para criar um histórico explícito e rastreável.

**Formato:** `prefixo: mensagem em modo imperativo`

**Prefixos mais comuns:**
- `feat`: Adiciona uma nova funcionalidade.
- `fix`: Corrige um bug.
- `docs`: Altera a documentação.
- `style`: Ajustes de formatação (espaços, vírgulas, etc.), sem impacto no código.
- `refactor`: Refatoração de código que não altera o comportamento final.
- `test`: Adiciona ou modifica testes.
- `chore`: Tarefas de build, configurações ou outras tarefas internas.

**Exemplos:**

| ✅ Bom | ❌ Ruim |
| :--- | :--- |
| `feat: adiciona autenticação via token JWT` | `login novo` |
| `fix: corrige cálculo de impostos no checkout` | `bugfix` |
| `refactor: simplifica módulo de pagamentos` | `mudanças no código` |

### Fluxo de Trabalho (Git Flow)
1.  **Sincronize:** Atualize sua branch principal (`main` ou `develop`) antes de iniciar.
    - `git checkout main && git pull`
2.  **Ramifique:** Crie uma nova branch para cada tarefa.
    - `git checkout -b feat/nome-da-funcionalidade`
3.  **Desenvolva:** Faça commits pequenos e frequentes com mensagens claras.
4.  **Teste:** Garanta que suas alterações não quebraram nada e que tudo funciona como esperado.
5.  **Envie:** Suba sua branch e abra um Pull Request (PR) para revisão de código.

---

## 📝 Documentação

Código e projetos bem documentados aceleram o desenvolvimento e facilitam a manutenção.

- **Código Autodocumentado:** Priorize nomes descritivos e funções pequenas que tornem o código intuitivo.
- **Comentários Estratégicos:** Use comentários apenas para explicar trechos complexos ou decisões de arquitetura.
- **README Completo:** Todo projeto deve ter um `README.md` com:
  - Instruções claras de instalação e execução.
  - Exemplos de uso.
  - Requisitos e dependências.
  - Como contribuir.

> **Lembre-se:** Boas práticas evoluem com o tempo. O importante é manter a mente aberta para a melhoria contínua.