#  Guia de Boas Práticas para Desenvolvedores na Autocom3

## 💻 Código Limpo

### Princípios Fundamentais

- **Comentários úteis e objetivos**: Comentários devem explicar o *porquê*, não o *como* (que deve estar claro no código).
- **Consistência com os padrões do projeto**: Siga convenções já adotadas, como nomes, estrutura de pastas e formatação.
- **Nomes claros e significativos**: Use nomes descritivos que expressem a intenção. Evite abreviações confusas.
- **Funções pequenas**: Cada função deve executar apenas uma tarefa.
- **Evite repetição e seguir o padrão DRY (Don't Repeat Yourself)**: Centralize lógica comum em funções reutilizáveis e evite duplicações.
- **Tratamento de erros adequado**: Trate exceções de forma clara. Evite blocos `try/catch` vazios ou sem logs úteis.


> **Dica**: Leia o código como se fosse um texto. Se for difícil de explicar, provavelmente precisa ser simplificado.


## 🌿 Controle de Versão

### Commits Padronizados (Conventional Commits)

Adote o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/) para manter o histórico claro e organizado.

**Prefixos comuns:**

- `feat`: Nova funcionalidade
- `fix`: Correção de bug
- `docs`: Alterações na documentação
- `style`: Formatação (espaços, vírgulas, identação)
- `refactor`: Refatoração (sem alterar comportamento)
- `test`: Adição ou alteração de testes
- `chore`: Tarefas internas (build, configs, etc.)

**Boas práticas:**

- Commits pequenos e frequentes
- Mensagens claras, no tempo presente e modo imperativo  
  Ex: `adiciona autenticação por token`

**Exemplos:**

| ✅ Bom | ❌ Ruim |
|--------|--------|
| `feat: adiciona função de login` | `adicionei umas coisas` |
| `fix: corrige bug na validação` | `correção` |
| `refactor: refatora módulo de pagamento` | `mudanças` |

---

### Fluxo de Trabalho

1. Atualize sua branch antes de começar
2. Crie uma branch por tarefa
3. Teste antes de abrir PR
4. Solicite revisão de código


## 📝 Documentação

### Código Autodocumentado

- Use nomes descritivos
- Extraia código complexo para funções com nomes claros
- Adicione comentários apenas quando necessário

### Documentação de Projeto

- README com instruções claras
- Exemplos de uso
- Requisitos e dependências
- Como contribuir 
---

>  **Lembre-se**: Boas práticas evoluem com o tempo. O importante é estar aberto a melhorias contínuas.
