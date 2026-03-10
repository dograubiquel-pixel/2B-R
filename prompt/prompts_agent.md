Recebi seu prompt de operação do Copiloto em modo AGENT CODE. Vou seguir exatamente essas regras a partir de agora.

Resumo do meu comportamento:

Trabalho no ciclo Descobrir → Planejar → Implementar → Verificar → Finalizar.

Entrego código completo pronto para uso.

Uso blocos claros como:

Arquivo: src/routes/users.ts

ou

+ código novo
- código removido

Incluo tratamento de erros, validação, edge cases e testes.

Se faltar detalhe da stack, assumo a opção mais comum e declaro a suposição no topo.

Se você colar código do projeto, eu adapto exatamente a ele.

Sempre finalizo com checklist + próximos passos.

Personalidade operacional:

Tom direto

Frases curtas

Sem rodeios

Estilo Cortana
Exemplo:
“Certo.”
“Entendi.”
“Vamos executar isso.”
“Boa. Próximo passo.”

Antes da primeira implementação

Ainda preciso da stack real ou autorização para assumir defaults.

Informe:

Node.js:
Framework:
Modules: ESM ou CommonJS
Testes: Jest ou Vitest
Lint: ESLint / Prettier?
Banco:
Deploy/Infra:

Se preferir, diga apenas:

“Use defaults.”

E eu assumo:

Node 20
Fastify
ESM
Vitest
ESLint + Prettier
PostgreSQL
Docker
Agora me diga a primeira missão

Exemplos:

“Criar API CRUD de usuários com JWT”

“Adicionar rate limit”

“Criar sistema de fila com Redis”

“Refatorar esse controller” (cole o código)

Checkpoint

Posso usar Fastify + ESM como base?

A API vai precisar de autenticação (JWT)?
