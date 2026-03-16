# URL Shortener API

Serviço backend para encurtamento de URLs desenvolvido com Node.js.

A aplicação permite gerar links curtos a partir de URLs completas e redirecionar o usuário automaticamente para o endereço original.

Este projeto foi criado como prática de desenvolvimento backend, focando em organização de código, manipulação de requisições HTTP e construção de serviços web simples.

---

## Objetivo do projeto

O objetivo da aplicação é simular o funcionamento de serviços de encurtamento de links como:

- Bitly
- TinyURL

O sistema recebe uma URL longa, gera um identificador curto e cria um link que redireciona para o endereço original.

---

## Tecnologias utilizadas

- Node.js
- JavaScript
- HTTP Server
- Arquitetura modular

---

## Funcionalidades

A API oferece as seguintes funcionalidades:

- criação de URL encurtada
- geração de identificadores curtos
- redirecionamento automático para a URL original
- organização modular da lógica do serviço

---

## Estrutura do projeto

A aplicação segue uma estrutura simples de backend:

```
src/
  routes/
  controllers/
  services/
  utils/

server.js
```

Essa organização separa responsabilidades da aplicação e facilita manutenção e evolução do código.

---

## Funcionamento do sistema

O fluxo básico da aplicação é:

1. o usuário envia uma URL longa
2. o sistema gera um identificador curto
3. a URL é armazenada
4. um novo link curto é criado
5. ao acessar o link curto o sistema redireciona para a URL original

---

## Como executar o projeto

Clone o repositório:

```bash
git clone https://github.com/DanAntunesDev/url-shortener-api
```

Acesse a pasta do projeto:

```bash
cd url-shortener-api
```

Instale as dependências:

```bash
npm install
```

Inicie o servidor:

```bash
npm start
```

Após iniciar, o serviço ficará disponível localmente para receber requisições.

---

## Possíveis melhorias futuras

Este projeto pode evoluir com diversas melhorias como:

- persistência em banco de dados
- contagem de acessos
- expiração de links
- autenticação de usuários
- interface administrativa
- estatísticas de acesso

---

## Autor

Daniel Antunes
