<style>
  h1,
h2,
h3 {
  color: white;
  border: 0px;
  margin-bottom: -5px;
  font-weight: bold;
}

.center {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: auto;
}

.text-center {
  text-align: center;
}

.content {
  margin-top: 20px;
  margin-bottom: 20px;
}

.divider-min {
  width: 155px;
  height: 1px;
  background-color: rgba(93, 93, 93, 0.334);
}

.sub-title {
  font-size: 16px;
  font-weight: 700;
}

#page {
  min-width: 80%;
  max-width: 80%;
  margin: auto;
}

@media screen and (max-width: 768px) {
  #page {
    max-width: 90%;
  }
}

.hidden {
  display: none;
}

/* Profile */

#intro img {
  position: absolute;
  top: 10px;
  left: 0px;
  right: 0px;
}

#intro img:hover {
  transform: scale(1.07);
  transition: all 1s ease-in-out;
  border-radius: 200px !important;
}

#intro img:hover {
  animation: pulse 1s ease-in-out forwards;
}

@keyframes pulse {
  0% {
    transform: scale(1) rotate(0deg);
    border-radius: 12px;
  }
  50% {
    transform: scale(1.1) rotate(1.5deg);
    border-radius: 120px 0px 12px 90px;
  }
  100% {
    transform: scale(1.07) rotate(1deg);
    border-radius: 120px 0px 12px 90px;
  }
}

#banner-profile {
  width: 100%;
  height: 120px;
  background-color: blue;
  border-radius: 10px;
  margin-top: 10px;
  margin-bottom: 50px;
}

.profile_name {
  font-size: 2rem;
  color: white;
  margin-top: 10px;
}

.profile_description {
  font-weight: 500;
  font-size: 18px;
}

/* Stacks */

#stacks {
  width: 100%;
}

table {
  min-width: 100%;
  width: 100%;
}

#content-stacks {
  display: flex;
  gap: 10px;
  justify-content: center;
}

.stacks-container {
  background-color: rgb(50 50 56);
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 5px;
  max-width: 250px;
  gap: 5px;
  padding: 5px;
}

.stacks-container:hover {
  background-color: rgb(70 70 76);
}

/* About */

#about,
#stacks,
#projects,
#statics {
  margin-top: 20px;
  padding-top: 20px;
}

#about_title {
  font-size: 1.8rem;
  color: white;
  margin-bottom: 10px;
}

/* Stacks */

.stacks-text {
  font-size: 18px;
  color: white;
  font-weight: 500;
}

/* Projetos */

#project-title {
  margin-bottom: 20px;
}

#projects h2 {
  font-size: 2rem;
  color: white;
  margin-bottom: 10px;
}

#projects p {
  font-size: 20px;
  color: white;
  font-weight: 500;
}

#projects .project-container {
  border-radius: 10px 20px;
  box-shadow: 0 0.75rem 2rem rgba(0, 0, 0, 0.175);
  margin-bottom: 40px;
  padding: 10px 30px;
  background-color: rgba(19, 19, 144, 0.055);
}

#projects .project-container {
  transition: transform 0.4s ease, box-shadow 0.4s ease;
  will-change: transform;
  cursor: pointer;
}

#projects .project-container:hover {
  transform: scale(1.03) rotate(0.5deg);
  box-shadow: 0 1.5rem 3rem rgba(0, 0, 0, 0.2);
}

#projects ul {
  padding: 0px;
  margin: 0px;
}

#projects ul li {
  list-style: none;
  font-size: 16px;
  color: rgb(213, 212, 212);
  font-weight: 400;
  margin-bottom: 10px;
}

/* Statics */

#statics-rocktseat,
#statics {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
  margin-top: 20px;
}

#statics-rocktseat {
  margin-top: 50px;
  flex-direction: row-reverse;
}

#statics-rocktseat-intro,
#statics-intro {
  background-color: rgb(59, 59, 87);
  padding: 20px;
  border-radius: 10px;
  width: 50%;
  text-align: center;
}

#statics-rocktseat h1,
#statics h1 {
  word-break: keep-all;
  font-size: 2.5rem;
  color: white;
  margin-bottom: 10px;
}

#statics-rocktseat h1::before,
#statics h1::before {
  content: "📊";
  display: flex;
  flex-direction: column;
}

#statics-rocktseat h1::before {
  content: "🚀" !important;
}

#statics-rocktseat h1 {
  font-size: 4.5rem !important;
}

#statics-rocktseat p,
#statics p {
  font-size: 18px;
  color: white;
  font-weight: 500;
}

#statics .static-container:hover,
#statics .static-container:hover {
  background-color: rgb(70 70 76);
}

#statics-rocktseat .static-container h3,
#statics .static-container h3 {
  font-size: 1.5rem;
  color: white;
  margin-bottom: 10px;
}

.statics-container__imgs img {
  width: 100%;
  height: auto;
  border: none;
  outline: none;
  box-shadow: none;
  margin: 0;
  margin-bottom: 20px;
}

.statics-container__imgs img:hover {
  transform: scale(1.05);
  transition: all 0.3s ease-in-out;
}

/* Social */

@media screen and (max-width: 768px) {
  #social {
    width: 90%;
    margin: auto;
  }
}

#social {
  margin: auto;
  width: 80%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 200px;
  flex-direction: row-reverse;
  margin: auto;
}

#social div:nth-child(1) {
  width: auto;
}

#social div:nth-child(2) {
  width: 40%;
}

#social h2 {
  font-size: x-large;
  text-align: left;
}

</style>

<div id="page">

<div id="intro">
  <div id="banner-profile"></div>
  <!-- Imagem/Profile -->
  <div class="profile-container">
    <img class="center" src="./imgs/profile.jpg" width="170px" height="170px" style="border-radius : 65px 45px 65px 45px; object-fit: cover;" title="Maxsuel por aqui ! 😉😀"/>
  </div>
  <h1 class="text-center profile_name">I'm Maxsuel David Oliveira! 😐</h1>
  <p align="center" class="profile_description" style="">
    💻 Develop FullStack JavaScript | React JS | React Native | Node.js | Microservices | Python | RPA. <br>
    <svg stroke="currentColor" fill="none" stroke-width="0" width="16" height="16" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" class="text-gray-200"><path fill-rule="evenodd" clip-rule="evenodd" d="M12.0015 1.25C8.17538 1.25 4.52505 3.51253 2.99714 7.08468C1.57518 10.4086 2.34496 13.2373 3.94771 15.6595C5.26177 17.6454 7.17835 19.4178 8.90742 21.0168L8.90824 21.0175C9.23768 21.3222 9.56031 21.6206 9.87066 21.9129L9.87231 21.9145C10.4473 22.4528 11.2112 22.75 12.0015 22.75C12.7919 22.75 13.5558 22.4528 14.1258 21.9144C14.4243 21.6396 14.7286 21.3592 15.039 21.0732C16.7869 19.4628 18.7254 17.672 20.0582 15.6609C21.6591 13.2362 22.4261 10.4045 21.0059 7.08468C19.478 3.51253 15.8277 1.25 12.0015 1.25ZM12 7C9.79086 7 8 8.79086 8 11C8 13.2091 9.79086 15 12 15C14.2091 15 16 13.2091 16 11C16 8.79086 14.2091 7 12 7Z" fill="currentColor"></path></svg> Brazil
  </p>
</div>

<div class="content" id="content-stacks">
  <div class="stacks-container">
  <img src="icons/javascript.svg" width=25>
    <span style="font-size : 16px; font-weight : 700;">JAVASCRIPT</span>
  </div>
  <div class="stacks-container">
    <img src="icons/javascript.svg" width=25>
    <span style="font-size : 16px; font-weight : 700;">NODEJS</span>
  </div>
  <div class="stacks-container">
    <img src="icons/react_native.svg" width=25>
      <span style="font-size : 16px; font-weight : 700;">REACT NATIVE</span>
  </div>
  <div class="stacks-container">
    <img src="icons/python.svg" width=25>
      <span style="font-size : 16px; font-weight : 700;">PYTHON</span>
  </div>
  <div class="stacks-container">
    <img src="icons/python.svg" width=25>
      <span style="font-size : 16px; font-weight : 700;">FLASKY</span>
  </div>
</div>

<div class="content" id="about">
  <h1 id="about_title">👨‍💻 Sobre mim</h1>
  <p style="font-size: 18px;">
  Olá! Me chamo Maxsuel David, sou um desenvolvedor apaixonado por tecnologia. Minha jornada começou cedo, com pequenos scripts em <code>.bat</code>, depois experimentando o <b>Google Sites</b>, até que mergulhei de vez em <b>HTML</b> e <b>PHP</b>. Com o tempo, vieram os cursos e, mais tarde, o <b>IFBA</b>, onde tive a oportunidade de fazer meu primeiro trabalho como <b>freelancer</b>, usando <b>HTML, CSS, PHP, MySQL</b> e <b>JavaScript</b>.<br><br>
  Desde então, desenvolvi diversos projetos como <b>freelancer</b>: <u>Desde links de pedidos integrados a sistemas de delivery, até plataformas de gestão de pedidos para óticas, sites institucionais e um sistema completo de avaliação de clientes.</u><br><br>
  No meio do caminho, enfrentei frustrações, prazos apertados, bugs inesperados, sistemas quebrando e noites mal dormidas. Cada obstáculo moldou minha trajetória e me fortaleceu como desenvolvedor.<br><br>
  Em 2024, decidi me aventurar no universo do <b>JavaScript</b>, impulsionado pelo crescimento da linguagem. No entanto, a rotina intensa acabou limitando meu tempo para me aprofundar. Mas 2025 chegou como um recomeço: agora, com foco total em <b>JavaScript</b> e <b>RPA</b>, estou reconstruindo minha carreira com mais maturidade, disciplina e paixão.<br><br>
  Afinal, não somos uma <code>const</code> — tudo muda, tudo evolui, tudo pode (e deve) ser refatorado. Estou redescobrindo esse universo e cada dia mais fascinado por ele. Fique à vontade para acompanhar minha jornada no <b>backend</b> com <b>JavaScript</b> e automações com <b>RPA</b>.
</p>
</div>

<div class="content" id="stacks">
  <h1 id="stacks-title">🚀 Tecnologias</h1>
  <p style="font-size : 18px">
  Um pouco das tecnologias que eu já conheço e estou conheçendo.
  </p>
<table>
<tbody>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/python.svg" width="25">
      <span class="sub-title">PYTHON</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Elaborando várias ideias, desde scraping até chatbots.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/docker.svg" width="25">
      <span class="sub-title">DOCKER</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Empacotando microserviços e testando tudo em containers.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/oracle.svg" width="25">
      <span class="sub-title">ORACLE</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Consultas robustas e integrações em sistemas legados.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/javascript.svg" width="25">
      <span class="sub-title">JAVASCRIPT</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Meu universo atual: lógica, eventos e muita DOM.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/figma.svg" width="25">
      <span class="sub-title">FIGMA</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Protótipos rápidos pra transformar ideias em tela.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/nodejs.svg" width="25">
      <span class="sub-title">NODE.JS</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Backend leve, rápido e cheio de automações.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/react.svg" width="25">
      <span class="sub-title">REACT</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      UIs dinâmicas com muita responsividade e hooks.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/sqlite.svg" width="25">
      <span class="sub-title">SQLITE</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Simples, direto e perfeito pra projetos locais.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/tailwindcss.svg" width="25">
      <span class="sub-title">TAILWIND CSS</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Estilo rápido, prático e com utilitários em tudo.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/express.svg" width="25">
      <span class="sub-title">EXPRESS.JS</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Minha base para APIs rápidas e bem organizadas.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/mongo.svg" width="25">
      <span class="sub-title">MONGODB</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Schema flexível e fácil de escalar com Node.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/css.svg" width="25">
      <span class="sub-title">CSS3</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Estilizando desde os tempos do float: left.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/postman.svg" width="25">
      <span class="sub-title">POSTMAN</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Testando, documentando e validando todas as rotas.
    </p>
  </td>
</tr>
<tr>
  <td>
    <div class="stacks-container">
      <img src="icons/git.svg" width="25">
      <span class="sub-title">GIT</span>
    </div>
  </td>
  <td>
    <p class="stacks-text">
      Versionando tudo com responsabilidade (e uns commits nervosos).
    </p>
  </td>
</tr>
</tbody>
</table>
</div>

<div class="content" id="projects">
  <h1 id="project-title">
  ✨ Projetos em destaque
  </h1>
  <div class="project-container">
    <h2>
      Próton ERP
    </h2>
    <p>
      Descrição do projeto
    </p>
    <ul>
      <li>
        Node.js <span> Usado para construir o meu backend.</span>
      </li>
      <li>
        Postgress <span>Banco de dados</span>
      </li>
      <li>
        Docker <span>Upload de um microservice que é a consulta por onde fica o backend.</span>
      </li>
      <li>
        React JS <span> Frontend para o cliente.</span>
      </li>
    </ul>
  </div>
  <div class="project-container">
    <h2>EstoqueFácil</h2>
    <p>
      App de contagem de estoque com leitura de planilhas e scanner de códigos de barras.
    </p>
    <ul>
      <li>
        React Native <span>Usado para desenvolver o app mobile.</span>
      </li>
      <li>
        JavaScript <span>Base de toda a lógica da aplicação.</span>
      </li>
      <li>
        XLSX <span>Importação e leitura de planilhas.</span>
      </li>
      <li>
        Expo <span>Facilitou o build e testes no celular.</span>
      </li>
    </ul>
  </div>
  <div class="project-container">
    <h2>Avaliali</h2>
    <p>
      Sistema completo para avaliação de clientes com painel administrativo.
    </p>
    <ul>
      <li>
        Node.js <span>Backend para controle das avaliações.</span>
      </li>
      <li>
        SQLite <span>Banco leve e direto no servidor.</span>
      </li>
      <li>
        JavaScript <span>Usado tanto no backend quanto em scripts do frontend.</span>
      </li>
      <li>
        HTML + CSS <span>Base do painel de administração.</span>
      </li>
    </ul>
  </div>
</div>

<div id="statics">
<div id="statics-intro">
  <h1 id="statics-title">
    Estatísticas GitHub
  </h1>
  <p>
  Desculpe a ausencia aqui no meu github... embreve novas atualizações.
  </p>
</div>
<div class="statics-container__imgs">
<img
  height="180em"
  src="https://github-readme-stats.vercel.app/api?username=MaxsuelOliveira&show_icons=true&theme=vue-dark&include_all_commits=true&count_private=true"
/>
<img
  height="180em"
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=MaxsuelOliveira&layout=compact&langs_count=8&theme=vue-dark"
/>
</div>
</div>

<div id="statics-rocktseat">
  <div id="statics-rocktseat__intro">
    <h1 id="statics-rocktseat__title">
      Estatísticas Rocketseat
    </h1>
  <p>
  Há tempos sonho em fazer parte da Rocketseat. Em 2025, finalmente me tornei aluno — e quem sabe, em breve, algo ainda maior aconteça, né @rocketseat? <a href="https://app.rocketseat.com.br/me/md-04583" title="Dá um pulo aqui" target="new_blank">🚀 Acompanhe minha jornada por aqui!</a>
  </p>
  </div>
</div>

<hr style="padding : 30px; display: flex; aling-items: center; margin-bottom: 50px;"

<div class="content" id="social">
  <div class="">

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/)
  [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/)
  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MaxsuelOliveira)
  [![Discord](https://img.shields.io/badge/Discord-181717?style=for-the-badge&logo=discord&logoColor=white)](https://github.com/)
  [![Rocketseat](https://img.shields.io/badge/Rocketseat-181717?style=for-the-badge&logo=rocketseat&logoColor=white)](https://app.rocketseat.com.br/me/md-04583)

  </div>
  <div class="">
    <h2>
    ✨ Sempre aprendendo, sempre evoluindo. Obrigado por visitar meu perfil! 🚀
    </h2>
  </div>
</div>
</div>