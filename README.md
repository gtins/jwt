# JWT Auth API – Node.js + Express

Este projeto é uma API de autenticação baseada em **JSON Web Token (JWT)** construída com **Node.js** e **Express**. É ideal para fins de estudo e demonstração de como proteger rotas e autenticar usuários de forma segura.

---

## Funcionalidades

- Login com validação de credenciais
- Geração de tokens JWT
- Proteção de rotas com middleware
- Senhas protegidas com bcrypt
- Validação de token para acesso a endpoints privados

---
## Como Executar
1. Instale as dependências:

npm install

2. Crie um arquivo .env na raiz do projeto e adicione:

SECRET=sua_chave_secreta

3. Inicie o servidor:

npm start

## Observações
Os usuários estão mockados no arquivo users.js.

Este projeto não usa banco de dados — ideal para aprendizado e testes locais.

Para uso real em produção, recomenda-se integrar com um banco de dados (ex: MongoDB) e usar HTTPS.
