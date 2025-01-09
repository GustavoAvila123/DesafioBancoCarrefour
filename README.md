<h1 align="center">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSViCoMGDM9XiBXvlyB07xGRIIidiLMPfDxyQ&s" alt="PGE" height="200" width="300">
    <br>
</h1>

<div style="display: flex; justify-content: center;">
<a href="https://github.com/GustavoAvila123/DesafioBancoCarrefour"><img src="https://img.shields.io/badge/-COMMITS-f44336?style=for-the-badge&logo=github&logoColor=white" width="100" height="22" style="margin-right: 5px;"/></a>
<a href="https://serverest.dev/#/"><img src="https://img.shields.io/badge/-API-1da750?style=for-the-badge&logo=internet-explorer&logoColor=White" width="60" height="22" style="margin-right: 5px;"/></a>
</div>

---

<h4 align="center" style="color: white; font-size: 20px;">
    🚧 AUTOMAÇÃO DE TESTES | BACK-END 🚧
</h4>

---

## <font color="white">💻 SOBRE O PROJETO</font>

<p style="color: white;">Este projeto é um conjunto abrangente de testes automatizados para <strong>garantir a funcionalidade e a integridade da API de Gerenciamento de Usuários.</strong><br>
Ele cobre todos os aspectos da API RESTful, incluindo operações de CRUD (criação, leitura, atualização e exclusão) de usuários.<br>

<strong>A estrutura dos testes assegura uma cobertura de 100%</strong>, incluindo a autenticação via token JWT, validação de limites de requisições e verificação de integridade dos dados dos usuários.<br>

Além disso, o projeto está integrado em uma pipeline de CI, gerando relatórios dos resultados dos testes, garantindo que a API seja testada de forma contínua e eficiente.<br>

A API da aplicação visa garantir uma experiência <strong>CONFIÁVEL</strong> e sem falhas para todos os usuários.</p>

---

## <font color="white">🛠️ TECNOLOGIAS UTILIZADAS</font>

<font color="white">O projeto foi desenvolvido utilizando as seguintes tecnologias:</font>

- [<span style="color: #f44336;">Postman</span>](https://www.postman.com/)
- [<span style="color: #f44336;">VS Code</span>](https://code.visualstudio.com/)

<font color="white">Além disso, temos as seguintes dependências:</font>

- [<span style="color: #f44336;">Newman</span>](https://www.npmjs.com/package/newman)

---

## <font color="white">📂 COMO BAIXAR O PROJETO</font>

<pre>
<code class="language-bash">
<span style="color: #f44336;"># Clonar o repositório</span>
$ https://github.com/GustavoAvila123/DesafioBancoCarrefour.git

<span style="color: #f44336;"># Instalar o Newman</span>
$ npm install -g newman

<span style="color: #f44336;"># Instalando extensão de Geração de Relatórios em HTML</span>
$ npm install -g newman-reporter-htmlextra

<span style="color: #f44336;"># Executando o Newman</span>
$ npx newman run ./usuario/Postman-files/usuario_collection.json -e ./usuario/Postman-files/usuario_environment.json

<span style="color: #f44336;"># Executando o reports</span>
$ newman run ./usuario/Postman-files/usuario_collection.json -e ./usuario/Postman-files/usuario_environment.json -r htmlextra
</code>
</pre>

## <font color="white">📝 RESUMO DA ESTRUTURA</font>

<p style="color: #FFFFFF;">
    🎬 NEWMAN:<br>
    <font color="#f44336">&#10004;</font> Onde armazenamos a execução da nossa automação.
</p>

<p style="color: #FFFFFF;">
    ⚪ POSTMAN FILES:<br>
    <font color="#f44336">&#10004;</font> usuario_Collection: Armazena todos os nossos testes referente aos ENDPOINTS DA API.<br>
    <font color="#f44336">&#10004;</font> usuario_Environment: Armazena todas as nossas variáveis de ambientes.<br>
</p>

<p style="color: #FFFFFF;">
    ⏯️ USUARIO COLLECTION:<br>
    <font color="#f44336">&#10004;</font> Página onde armazenamos os nossos testes dos ENDPOINTS.<br>
</p>

<p style="color: #FFFFFF;">
    🔒 USUARIO ENVIRONMENT:<br>
    <font color="#f44336">&#10004;</font> Página onde armazenamos todas as nossas variáveis de ambientes.<br>
</p>

## <font color="white">🔍 OVERVIEW DOS TESTES</font>

<p style="color: #FFFFFF;">
    <strong style="color: #f44336;">SERVEREST:</strong><br>
    <p style="text-align: justify; margin-left: 50px;">
    <strong>Usuário:</strong> Este projeto implementa testes automatizados para a API de gerenciamento de usuários, cobrindo operações de CRUD (criação, leitura, atualização e exclusão). Os testes validam a autenticação via token JWT e garantem que a API respeite o limite de 100 requisições por minuto. São verificadas também a estrutura e a integridade dos dados, como campos obrigatórios no cadastro de usuários. Além disso, os testes são integrados a uma pipeline de CI para execução contínua e geração de relatórios. O objetivo é garantir 100% de cobertura e a qualidade da API.
    </p>

<h2 style="color: white;">✍ AUTOR</h2>
  <table>
  <tr>
    <td align="center">
      <a href="www.linkedin.com/in/gustavo-ávila-1168a8150">
        <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/132934043?s=400&u=d70e99353630191829cdfbc95f9f48c0a66299e8&v=4" width="100px;" alt=""/>
        <br />
         <sub style="color: white;"><b>Gustavo Ávila</b></sub>
      </a>
      <br />
      <a title="GUSTAVO ÁVILA"><sub style="color: white;"><b>Analista de Qualidade<b></a>
      <br/>
      <br/>
      <a href="mailto:gustavotoiansk@icloud.com">
        <img src="https://img.shields.io/badge/-gustavotoiansk@icloud.com-f44336?style=flat-square&logo=Gmail&logoColor=white" alt=""/>
      </a>
      <td align="center">
    </td>
  </tr>
</table>