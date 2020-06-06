<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src="./github-assets/banner.png" />
</h1>

<h4 align="center"> 
	 Next Level Week 1.0 🚀
</h4>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/diego64/teste?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/diego64/teste">

  	
  <a href="https://www.linkedin.com/in/leonardo-dev/">
    <img alt="Made by diego64" src="https://img.shields.io/badge/made%20by-Diego--Ferreira-%2304D361">
  </a>
	
  
  <a href="https://github.com/diego64/teste/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/diego64/teste">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/diego64/teste/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/diego64/teste?style=social">
  </a>
</p>


## 💻 Sobre o projeto

♻️ Ecoleta - é uma forma de conectar empresas e entidades de coleta de resíduos orgânicos e inorgânicos as pessoas que precisam descartar seus resíduos de maneira ecológica.

As empresas ou entidades poderão se cadastrar na plataforma web enviando:
- Uma imagem do ponto de coleta
- Nome da entidade, email e whatsapp
- Endereço para que ele possa aparecer no mapa
- Além de selecionar um ou mais ítens de coleta: 
  - Lâmpadas
  - Pilhas e baterias
  - Papéis e papelão
  - Pesíduos eletrônicos
  - Pesíduos orgânicos
  - Óleo de cozinha

Os usuários terão acesso ao aplicativo móvel, onde poderão:
- Navegar pelo mapa para ver as instituições cadastradas
- Entrar em contato com a entidade através do E-mail ou WhatsApp

Projeto desenvolvido durante a **NLW - Next Level Week 1.0** oferecida pela [Rocketseat](rs).
O NLW é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.


## 🎨 Layout

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/Ecoleta?node-id=136%3A546">
  <img alt="Made by leon-carvalho" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

### Frot-End 💻

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./github-assets/home-web.svg" width="300px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./github-assets/cadastro-web.svg" width="200px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./github-assets/sucesso-web.svg" width="300px">
</p>

<p align="center">
  
</p>

### Mobile 📲

<p align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./github-assets/home-mobile.png" width="200px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./github-assets/detalhes-mobile.svg" width="200px">
</p>

<p align="center">
  
</p>

## 🔨 Tecnologias utilizadas

As seguintes tecnologias foram usadas na construção do projeto:

- [Node.js][nodejs]
- [TypeScript][typescript]
- [React][reactjs]
- [React Native][rn]
- [Expo][expo]

## 📁 Estrutura do Projeto

Podemos considerar este projeto como sendo divido em três partes:
1. Back End 
2. Front End 
3. Mobile

👉 Tanto o Front End quanto o Mobile precisam que o Back End esteja sendo executado para funcionar 👈

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js][nodejs]. 
Além disto é bom ter um editor para trabalhar com o código como [VSCode][vscode]

### 📡 Rodando o Back End (Servidor)

```bash
# Clone este repositório
$ git clone https://github.com/diego64/Next-Level-Week-1.0_Booster

# Acesse a pasta do projeto no terminal/cmd
$ cd Next Level Week (Trilha Booster)

# Vá para a pasta server
$ cd server

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333

# Para poder crair uma tabela localmente conforme o padrão do sistema, basta criar um srcipt dentro do arquivo package.json com a seguinte linha: "knex:migrate": "knex --knexfile knexfile.ts migrate:latest"... Depois é só rodar com o seguinte comando no seu terminhal:
$ npm run knex:migrate
```

### 💻 Rodando a Aplicação Web (Front End)

```bash
# Clone este repositório
$ git clone https://github.com/diego64/Next-Level-Week-1.0_Booster

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Next Level Week (Trilha Booster)

# Vá para a pasta da aplicação Front End
$ cd mobile

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ expo start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```

### 📱 Rodando a Aplicação Mobile 

```bash
# Clone este repositório
$ git clone https://github.com/leon-carvalho/Ecoleta

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Next Level Week (Trilha Booster)

# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000

# Escanea o QR Code 
```

## ✌ Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)


## 📝 Licença

Este projeto esta sobe a licença MIT. Veja a [LICENÇA](license) para saber mais.


[nodejs]: https://nodejs.org/
[typescript]: https://www.typescriptlang.org/
[expo]: https://expo.io/
[reactjs]: https://reactjs.org
[rn]: https://facebook.github.io/react-native/
[yarn]: https://yarnpkg.com/
[vscode]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[license]: https://opensource.org/licenses/MIT
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[prettier]: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
[rs]: https://rocketseat.com.br