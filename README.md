# URL Shortener API

Serviço backend para encurtamento de URLs desenvolvido com Node.js.  
A aplicação permite gerar links curtos a partir de URLs completas e redirecionar o usuário automaticamente para o endereço original.

Este projeto foi criado como prática de desenvolvimento backend, focando em organização de código, manipulação de requisições HTTP e construção de serviços web simples.

---

# Objetivo do projeto

O objetivo da aplicação é simular o funcionamento de serviços de encurtamento de links, como:

- Bitly
- TinyURL

O sistema recebe uma URL longa, gera um identificador curto e cria um link que redireciona para o endereço original.

---

# Tecnologias utilizadas

- Node.js
- JavaScript
- HTTP server
- arquitetura modular

---

# Funcionalidades

A API oferece as seguintes funcionalidades:

- criação de URL encurtada
- geração de identificadores curtos
- redirecionamento automático para a URL original
- organização modular da lógica do serviço

---

# Estrutura do projeto

A aplicação segue uma estrutura simples de backend:

src/
routes/
controllers/
services/
utils/

server.js


Essa organização separa as responsabilidades da aplicação, facilitando manutenção e evolução do código.

---

# Funcionamento do sistema

O fluxo básico da aplicação é:

1. O usuário envia uma URL longa
2. O sistema gera um identificador curto
3. A URL é armazenada
4. Um novo link curto é criado
5. Ao acessar o link curto, o sistema redireciona para a URL original

---

# Como executar o projeto

Clone o repositório:
git clone https://github.com/DanAntunesDev/url-shortener-api


Instale as dependências:
npm install


Inicie o servidor:
npm start


Após iniciar, o serviço ficará disponível localmente para receber requisições.

---

# Possíveis melhorias futuras

Este projeto pode evoluir com diversas melhorias, como:

- persistência em banco de dados
- contagem de acessos
- expiração de links
- autenticação de usuários
- interface administrativa
- estatísticas de acesso

---

# Autor

Daniel Antunes
