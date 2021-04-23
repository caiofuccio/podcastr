<p align="center">
	<img alt="GitHub language count" src="https://img.shields.io/github/languages/count/caiofuccio/podcastr">
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/caiofuccio/podcastr">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/caiofuccio/podcastr">
  <img alt="status" src="https://img.shields.io/badge/status-finished-success">
  <a href="https://github.com/caiofuccio">
	  <img alt="Feito por Caio Fuccio" src="https://img.shields.io/badge/feito%20por-Caio%20Fuccio-9cf">
	<a/>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
</p>
<br/>

<h1  align="center">
  <img alt="Podcastr" src="./public/logo.svg" width="400px">
</h1>
<br/>

<p align="center">
 <a href="#-sobre">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a> •
 <a href="#-licença">Licença</a>
</p>
<br/>

<h4 align="center"> 
	🚧   Em construção (melhorias)   🚧
</h4>
<br/>

---

## 💻 Sobre

O Podcastr é um web app para ancoragem de episódios de podcast com um player embutido, onde você pode ouvir seus episódios favoritos.

Essa aplicação foi feita utilizando React, Next.js, Typescript, Sass e o servidor utilizado é do tipo Fake API com JSON Server.

Ela foi construída durante a quinta edição do Next Level Week, oferecido pela Rocketseat, na trilha de React.

<br/>

---

## ⚙️ Funcionalidades

A aplicação é do tipo Single Page Application (SPA) e conta com uma página home onde podem ser vistos os últimos episódios lançados, todos os episódios e conta com um player para reproduzir os episódios. Ao clicar em qualquer episódio você será redirecionado(a) à página de detalhes, que conta com a descrição detalhada do mesmo.

Na página Home você pode:

- Visualizar e selecionar episódios para ouvir
- Entrar na página dos episódios
- Ver informações como duração, participantes e data de publicação.

Na página de cada episódio você pode:

- Ver todas as informações apresentadas na home e a descrição do episódio em detalhes
- Reproduzir o episódios

No player, que sempre estará visível, você pode:

- Visualizar qual episódio está sendo reproduzido
- Dar play, pausar, avançar para o próximo episódio ou retroceder
- Alterar o tempo de reprodução a partir do Slider
- Selecionar o modo aleatório
- Selecionar a repetição do episódio

<br/>

---

## 🖼️ Layout

<br/>
<img alt="Tela Home" src="readme_images/home-player-off.png">
<img alt="Tela Home com player tocando episódio" src="readme_images/home-player-on.png">
<img alt="Tela do episódio" src="readme_images/episode-page.png">

<br/>
<br/>

<p align="center">
  <img alt="Gif com demonstração de uso da aplicação" src="readme_images/podcastr.gif">
<p/>

<br/>

---

## 🧰 Como executar

    # Clone o repositório
    $ git clone git@github.com:caiofuccio/podcastr.git

    # Instale as dependências
    $ yarn

    # Inicie a Fake API com JSON Server
    $ yarn server

    # Execute a aplicação
    $ yarn start

    # A aplicação será aberta na porta:3000 - acesse https://localhost:3000

<br/>

---

## 🚀 Tecnologias

<p align="center">
	<img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/>
	<img alt="CSS3" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>
	<br/>
	<img alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
	<img alt="TypeScript" src="https://img.shields.io/badge/typescript%20-%23007ACC.svg?&style=for-the-badge&logo=typescript&logoColor=white"/>
  <br/>
  <img alt="React" src="https://img.shields.io/badge/react%20-%2320232a.svg?&style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
  <img alt="Next JS" src="https://img.shields.io/badge/nextjs-%23000000.svg?&style=for-the-badge&logo=next.js&logoColor=white"/>
  <img alt="SASS" src="https://img.shields.io/badge/SASS-hotpink.svg?&style=for-the-badge&logo=SASS&logoColor=white"/>
	<br/>
<p/>

<br/>

---

## 👨‍💻 Autor

<p align="center">
	<img width="120px" alt="Caio Fuccio" src="https://avatars.githubusercontent.com/u/62528140?s=460&u=f323d1d9a12ba8b63b9d2bdff4502f29f6a68416&v=4"/>
	<br/>
	<strong>Caio Fuccio</strong>
	<br/>
	<sub> Front-End Developer | ReactJS</sub>
	<br/>
	<br/>
	<a href="https://www.linkedin.com/in/caiofuccio/">
		<img alt="Linkedin badge" src="https://img.shields.io/badge/-Caio%20Fuccio-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/caiofuccio/">
	</a>
	<a href="mailto:caio@gmail.com">
		<img alt="Linkedin badge" src="https://img.shields.io/badge/-caio.fuccio@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:caio.fuccio@gmail.com">
	</a>
</p>

<br/>

---

## ⚖️ Licença

Este projeto está sob a licença MIT.

Acesse o arquivo de [LICENSE](./LICENSE) para mais informações.
