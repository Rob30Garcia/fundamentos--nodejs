<h1 align="center">
  Primeiro projeto em Node.js
</h1>

<p align="center">
  Um projeto em node.js para aprender os conceitos mais básicos. 
</p>

<p align="center">
  <img src="https://img.shields.io/badge/node-v18.13.0-%23339933">
  <img src="https://img.shields.io/badge/status-finish-%23339933">
  <img src="https://img.shields.io/badge/license-MIT-green">
</p>

:notebook: Tabela de conteúdos
=================
<!--ts-->
  - [Tabela de Conteúdos](#tabela-de-conteúdos)
  - [Sobre](#Sobre)
  - [Funcionalidades](#Feature)
  - [Instalação](#instalação)
  - [Como usar](#como-usar)
<!--te-->

# :grey_question: Sobre

Um projeto para aprender alguns conceitos básicos em node.js como uso de streams, database com arquivos e uso de rotas para api como GET, POST, PUT e DELETE.

Além disso, foi feito o middleware para ler o json. Também o uso Regex para ler o params e o query da rota.

# :hammer: Funcionalidades

- [x] Cadastro de usuário
- [x] Listagem de usuário
- [x] Listagem de usuário filtrando pelo email e o nome
- [x] Atualização do usuário através do id
- [x] Deletar o usuário através do id

# :rocket: Instalação

- Clone o projeto
- Com o repositório clonado rode npm install

  ```bash
  npm install
  ```

São dois processos diferentes para entender o conceito de stream e rotas.

Para rodar a aplicação com as rotas:

- Para pode rodar o 

  ```bash
  npm run dev
  ```

- Importe o arquivo insomnia na pasta e use as rotas relacionadas e users

Para rodar a aplicação com streams:

- Para a parte de stream precisa rodar o 

  ```bash
  node streams/fake-upload-to-http-stream.js
  ```

- em seguida rodar o 

  ```bash
  node streams/fake-upload-to-http-stream.js
  ```

  - em seguida deve aparecer um resultado de 1 a 5.

# :notebook: Como usar

Depois que a aplicação estiver rodando precisamos usar o insomnia para fazer as requisições para pelas rotas:

- Import o arquivo "Insomnia-All_2023-02-26.json" no próprio insomnia.

- Na rota GET "List User" pode fazer sem ou com o filtro usando query params

- Na rota POST "Create User", no body precisa colocar o nome e o email.

- Na rota de PUT "Update User", no body precisa colocar o nome e o email, além de na url precisa colocar o id do user que vai ser modificado.

- Na rota de DELETE "Delete User", na url precisa do id do user para ser deletado do banco de dados.

# :computer: Tecnologias

- [Node.js](https://nodejs.org/en/)

# :white_check_mark: Autor

Feito com :heart: por Robert Garcia :ok_hand: Entre em contato. 

# Licença

This project could be used by anyone! MIT License

Copyright :copyright: 2023 - Primeiro projeto em node.js
