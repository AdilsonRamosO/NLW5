<div align="center"><img src="./doc-readme/icon.png" width="200" alt="Logo do Aplicativo">
</div>
<h1 align="center">Plant Manager</h1>
<p align="center">Aplicativo que gerencia cuidados com as plantas.</p>

<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#funcionalidades">Funcionalidades</a> • 
 <a href="#instalacao">Instalação</a> •
 <a href="#utilizacao">Utilização</a> •
 <a href="#autor">Autor</a> •  
 <a href="#licenca">Licença de uso</a>
</p>

<h2 id="objetivo">🎯 Objetivo</h2>
<p>Aplicativo desenvolvido durante a semana NLW#5 da <a href="https://rocketseat.com.br/">Rocketseat</a> como forma de aprimorar meus conhecimentos nas tecnologias React e React Native.</p>
<p>O layout original do plantmanager está disponível <a href="https://www.figma.com/file/IhQRtrOZdu3TrvkPYREzOy/PlantManager/duplicate?node-id=0%3A1">aqui</a></p>

<h2 id="tecnologias">🛠 Tecnologias</h2>

<p>Configurações do ambiente disponível <a href="https://www.notion.so/Configura-es-do-ambiente-79e0e4c3e992462a9b11f2745b0f2785">aqui</a></p>

<ul style="list-style-type:none">
  <li>
    <img src="./doc-readme/nodejs-16x16.png">
    <a href="https://nodejs.org/en/">Node.js</a>
  </li>
  <li>
    <img src="./doc-readme/expo-16x16.png">
    <a href="https://expo.io/">Expo</a>
  </li>
  <li>
    <img src="./doc-readme/react-16x16.png">
    <a href="https://reactjs.org/">React</a>
  </li>
  <li>
    <img src="./doc-readme/react-16x16.png">
    <a href="https://reactnative.dev/">React Native</a>
  </li>
</ul>

<p>Caso queria executar em um dispositivo virtual, uma das seguintes ferramentas pode ser usada:</p>
<ul style="list-style-type:none">
  <li>
    <img src="./doc-readme/androidStudio-16x16.png">
    <a href="https://developer.android.com/studio">Android Studio</a>
    ou
    <img src="./doc-readme/genymotion-16x16.png">
    <a href="https://www.genymotion.com/">Genymotion</a>
  </li>
</ul>

<h2 id="funcionalidades">✅ Funcionalidades</h2>

<ul style="list-style-type:none">
  <li>[X] Armazenamento do nome do usuário</li>
  <li>[X] Listagem de plantas</li>
  <li>[X] Listagem de categorias</li>
  <li>[X] Cadastro de plantas</li>
  <li>[X] Remoção de plantas cadastradas</li>
  <li>[X] Cadastro de notificação de cuidado com as plantas</li>
  <li>[X] Exibição de notificação</li>
</ul>

<h2 id="instalacao">🏃 Instalação</h2>

Clone o repositório, depois entre nele e instale as dependências 
```Bash 
  git clone https://github.com/AdilsonRamosO/NLW5
  cd plantmanager
  yarn install 
```

## Como utilizar o projeto

Para simular dados vindos de uma API e com um *delay*, foi utilizado a lib [json-server](https://github.com/typicode/json-server).
Por isso, antes de rodar o projeto, suba o servidor com o comando abaixo.
Lembre-se de alterar para o IP do seu computador.
```
json-server ./src/services/server.json --host 192.168.0.x --port 3333 --delay 700
```

No arquivo `src/services/api.ts` altere o `baseURL` para o IP do seu computador.

Após isso, basta rodar o projeto com o comando
```
yarn start
```
No seu celular baixe o app 'Expo go' e leia o QR code que irá abrir em seu navegador.

<h2 id="autor">💻 Autor</h2>
<p>Por Adilson Ramos 🏡 Me encontre:</p>

[![Linkedin Badge](https://img.shields.io/badge/-AdilsonJr.-blue?style=flat-square&logo=Linkedin&logoColor=white&link=#)](https://www.linkedin.com/in/adilson-ramos-9056761b9/)
[![Gmail Badge](https://img.shields.io/badge/-junior.ramos.contato@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:junior.ramos.contato@gmail.com)](mailto:junior.ramos.contato@gmail.com)

<h2 id="licenca">📝 Licença de uso</h2>
<p>Este projeto está sob a licença do MIT.</p>