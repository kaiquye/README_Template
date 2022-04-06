<!-- PROJECT SHIELDS -->

[![PRETTIER](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://gitter.im/jlongster/prettie)
<!-- PROJECT -->
<br />
<p align="center">
  <h1>

Portal Gente Gestão 🔰

  </h1> 
  <p align="center">
    <img src="https://user-images.githubusercontent.com/67064886/130372741-641ab606-fd6c-45bc-8570-ae219c68abfc.png" alt="Logo" >
    <br />
    <br />
    <a href="https://github.com/Tora-Transportes/GESTAO_ACESSOS/issues">Report Bug</a>
    ·
    <a href="https://github.com/Tora-Transportes/GESTAO_ACESSOS/issues">Request Feature</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->

## 🤔 Começando

Este programa, é responsável por automatizar todo o processo de recrutamento seleção, aceite de novos colaboradores.

<br />

<h2>⚠️ Pré-requisitos</h2>
- Node.Js Version 14.16.0 

+ Download : https://github.com/coreybutler/nvm-windows/releases/tag/1.1.9


<h2>👷 Construído com </h2>

Principais ferramentas.

+ Server 
  + <a href="https://www.npmjs.com/package/helmet" >  helmet </a> ajuda a proteger aplicativos Express definindo vários cabeçalhos HTTP
  + <a href="https://www.npmjs.com/package/express-jwt" >  express-jwt </a> ajuda a proteger aplicativos Express definindo vários cabeçalhos HTTP
  + <a href="https://www.npmjs.com/package/helmet" >  express </a> Estrutura web.
  + <a href="https://www.npmjs.com/package/express" >  compression </a> ajuda a proteger aplicativos Express definindo vários cabeçalhos HTTP
  + <a href="https://www.npmjs.com/package/body-parser" >  body-parser </a> Analisar os corpos de solicitação de entrada em um middleware antes de seus manipuladores, disponíveis sob a propriedade.req.body .
  + <a href="https://www.npmjs.com/package/bcrypt" >  bcrypt </a> criptografia de senhas . HTTP
  + <a href="https://www.npmjs.com/package/axios" >  axios </a> HTTP baseado em promessas para o navegador e NodeJs
  + <a href="https://www.npmjs.com/package/socket.io" >  socket.io </a>  permite a comunicação bidirecional em tempo real baseada em eventos.
  + <a href="https://www.npmjs.com/package/sharp" > sharp </a> converter imagens grandes em formatos comuns para imagens menores
  + <a href="https://www.npmjs.com/package/nodemailer" > nodemailer </a> Envia e-mails pelo Node.js.
+ Client
  + <a href="https://www.npmjs.com/package/material-ui" >  material-ui </a>  componentes React que implementam a especificação design de material do Google.
  + <a href="https://www.npmjs.com/package/axios" >  axios </a> HTTP baseado em promessas para o navegador e NodeJs
  + <a href="https://www.npmjs.com/package/nodemailer" > Redux  </a> Gerenciamento de estados.



<!-- Implantação -->
<h1>⚙️ Implantação </h1>

  + 📧 Conexão com SOLIDES-RH
    + A conexão é feita pela API do Solides RH. 
    + O Token de acesso pode ser copiado na parte de configurações do painel administrativo do SolidesRH.
    + **Diretório**
    + + **api** : src/config/setupSolides.
    + + **Controller** : modules/solides.
    
  + 📧 Envio de e-mail 
    + Todos os e-mails são enviado por padrão pelo endereço : **nao_responda@tora.com.br** senha : *********
    + **Casos de envio** :
    + + Redefinição de senha
    + + Aprovação de candidato.
    + + Rejeição de candidato.
    + + Criar nova vaga.
    
   + 📧 Estrutura de pastas.
     + **Server**
     + /Modules 
     + + Routes/Controller/Model
     + /Database
     + + Database Config
     + /Doc 
     + + Documentation API config
     + /Email
     + + Send e-mail
     + /Middleware
     + + jsonwebtoken/logger/helmet/response err
     + /Utils
     + + Configs
  
    + 📧 




## 🤖 Publicação


**-** <a href="https://genteegestao.tora.com.br" target="_blank">Frontend</a>

**-** <a href="https://genteegestao.tora.com.br/api/docs" target="_blank">Backend</a>

<br />


<!-- INSTALLATION -->

## 🔨 Padrão de instalação

```bash
git clone https://github.com/Tora-Transportes/GESTAO_ACESSOS.git
$ cd GESTAO_ACESSOS/client  -and-   GESTAO_ACESSOS/server
$ npm install
```

Considerações:

- Este programa foi executado em Linux / Windows 😄

<br>

<!-- SETUP -->

## 🔥 Setup

#### Copie ou renomeie o arquivo

```
$ cp .env-examples .env 
```

<!-- RUNNING TESTS -->

## 🤓 Documentação 

* Access swagger http://localhost:5000/api/docs 🥇

<br>

<!-- RUNNING -->

## 🚀 Execução

```
$ /client npm start 
```
```
$ /server npm start 
```

#### Ou execute com Docker 🐳

```
$ docker-compose up -d
```

<br>

<!-- LICENSE -->

## 🔓 Licença
TORA TRANSPORTES

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
