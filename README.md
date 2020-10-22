<h1 align="center">
  <img alt="Ícone do projeto" title="" src=".github/favicon.png" width="" />
</h1>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=04D361">
</p>

<h1 align="center"> :camera_flash: Screenshots </h1>

<div align="center">
  <h2 align="center">Desktop</h2>
  <img src=".github/desktop.svg" alt="Exemplo da interface no desktop" style="width: 100%;">  
</div>

<div align="center">
  <h2 align="center">Mobile</h2>
  <img src=".github/mobile.svg" alt="Exemplo da interface no mobile" height="600px;">  
</div>

## :gear: Requisítos

- [ ] [Node.js](https://nodejs.org/en/) ( Obrigatório )
- [ ] [GIT](https://git-scm.com/) ( Opcional )

## :rocket: Tecnologias

- [x] [Node.js](https://nodejs.org/en/)
- [x] [Express.js](https://expressjs.com/)
- [x] [Nodemon](https://nodemon.io/)
- [x] [dotenv](https://www.npmjs.com/package/dotenv)
- [x] [nunjucks](https://mozilla.github.io/nunjucks/)
- [x] [sqlite-async](https://www.npmjs.com/package/sqlite-async)

## :computer: Projeto

Aplicação web desenvolvida na segunda edição da next level week.

## :bookmark: Layout

Você pode visualizar o layout desse projeto clicando [aqui](https://proffy-roger.herokuapp.com/)

## :scroll: Banco de dados

Caso você queira resetar o banco de dados, basta ir na pasta src/database e excluir o arquivo database.sqlite,
e com o terminal aberto execute `npm run db` no root do projeto.

## :checkered_flag: Updates

Este projeto está em constante evolução

## :bookmark_tabs: Ideias de implementação

- [ ] Adiconar um novo banco de dados
- [ ] Melhorar a responsividade
- [ ] Adicinar tela de cadastro concluído

## :open_file_folder: Estrutura de diretórios

```
|-- .github/
|-- public/
  |-- assets/
  |-- pages/
  |-- scripts/
  |-- styles/
  |-- index.html
|-- src/
  |-- config/
    |-- index.js
  |-- controllers/
    |-- index.js
  |-- database/
    |-- createProffy.js
    |-- database.sqlite
    |-- db.js
  |-- utils/
    |-- format.js
  |-- app.js
  |-- routes
    |-- routes.js
  |-- server.js
|-- .env
|-- .gitignore
|-- LICENSE.md
|-- package.json
|-- package-lock.json
|-- README.md
```

## :arrow_down: Instalação

- `git clone https://github.com/sophiapinto/siteproffy.git`;
- `cd siteproffy`;
- `npm install | yarn install`;
- `npm start | yarn start`.

## :thinking: Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
