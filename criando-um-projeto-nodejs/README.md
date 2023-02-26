<h1 align="center">
  Primeiro projeto em Node.js
</h1>

<p align="center">
  Um projeto em node.js para aprender os conceitos mais básicos. 
</p>

<p align="center">
  <img src="https://img.shields.io/badge/node-v18.13.0-%23339933">
  <img src="https://img.shields.io/badge/status-finish-%23339933">
</p>

Tabela de conteúdos
=================
<!--ts-->
  [Sobre](#Sobre)
  [Tabela de Conteúdos](#tabela-de-conteúdos)
  [Instalação](#instalação)
  [Como usar](#como-usar)
<!--te-->

# Sobre

Um projeto para aprender alguns conceitos básicos em node.js como uso de streams, database com arquivos e uso de rotas para api como GET, POST, PUT e DELETE.

Além disso, foi feito o middleware para ler o json. Também o uso Regex para ler o params e o query da rota.

# Instalação

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



