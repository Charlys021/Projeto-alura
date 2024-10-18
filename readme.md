<h1 align="center"> Projeto Alura Books</h1>

<p align="center">
Este é o 3º projeto desenvolvido que faz parte da Formação Front End da Platafroma Alura, apresentado por Guilherme Lima, Rafaella Ballerini e Monica Hillman.<br/>
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>



<br>

  <div align="center">
    <a target="_blank" href="https://robertojunnior.github.io/alura-books/">
    <img width="90%" src="img/projeto-figma.png" alt="alura-books">
    </a>
  </div>

<br>
<br>



## 🚀 Tecnologias

Esse projeto está sendo desenvolvido com as seguintes tecnologias:

<li> HTML
<li> CSS
<li> Figma
<li> Git and GitHub


## 💻 Projeto

Foi utilizado a metodologia "BEM" neste projeto aplicado pela Instrutora Monica Hillman, onde ela adotou a abordagem de construção do projeto como "Mobile First", que se entende por qualquer projeto web que leve em consideração a usabilidade em dispositivos móveis primeiro.

Ela revisou alguns conceitos como flexbox, listas e ancoras, criou um menu suspenso interativo, com botão hamburguer sem o uso do JavaScript, algo que achei bem legal e ainda estilizamos com uso de pseudo classes ":hover" e ":checked", tendo o 1º contato também com combinadores tipo "~" no css. Também criamos campos de pesquisa com inputs e label.<br>

A Monica nos apresentou o <a target="_blank" href="https://swiperjs.com/">"SwiperJs"</a>, que é um framework de javascript criado e utilizado para a apresentação na forma de slides de uma forma moderna, estilizada e fácil de se implementar, disponível também em Angular, Vue, Solid, Svelte e React.<br>

Também aplicamos o uso de "media-queries" para implementação dos layouts de responsividade conforme projeto desenvolvido no Figma para: <br>

<li>Mobile (min-width; 428px); 
<li>Tablet (min-widtth: 1024px);
<li>Desktop (min-width: 1728px).<br>

Como uma de minhas telas que utilizo é a do notebook de 15.6" com resolução HD, adaptei o código também para sua resolução com mais um media-querie screen (min-width: 1366px) com alguns ajustes adicionais, que se adapou perfeitamente ao projeto original.<br>

Ao final do curso realizamos testes de usabilidade, responsividade multi telas e na folha de estilo "header.css", classe ".lista__menu", adicionei um "z-index: 2" devido ela estar aparecendo sob o "pagination" do primeiro carrossel no "Mobile", zerando qualquer "bug" visual no projeto.<br>
