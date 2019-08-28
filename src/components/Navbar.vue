<template>
  <nav class="navbar navbar-expand-lg container">
      <!-- Link com a Logo -->
      <a class="navbar-brand" href="#">
        <img class="img-fluid" src="../assets/img/logo.png" alt="Logo">
      </a>
      <!-- Botão 'Hamburguer' para Collapse -->
      <button class="navbar-toggler navbar-light" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <!-- Conteúdo expandido do navbar -->
      <div class="collapse navbar-collapse justify-content-center" id="navbarSupportedContent">
        <ul class="navbar-nav">
          <!-- Home -->
          <li class="nav-item active">
            <a class="nav-link" href="#">HOME</a>
          </li>
          <!-- Sobre -->
          <li class="nav-item">
            <a class="nav-link" href="#">SOBRE</a>
          </li>
          <!-- Receitas -->
          <li class="nav-item">
            <a class="nav-link" href="#">RECEITAS</a>
          </li>
          <!-- Notícias -->
          <li class="nav-item">
            <a class="nav-link" href="#">NOTÍCIAS</a>
          </li>
          <!-- Contato -->
          <li class="nav-item">
            <a class="nav-link" href="#">CONTATO</a>
          </li>
          <!-- Procura -->
          <li class="nav-item">
            <img class="cursor-pointer" src="../assets/img/search.png" alt="Procura">
          </li>
        </ul>
      </div>
    </nav>
</template>

<style>

  /* Configurações Gerais */
  * {
  font-family: 'Montserrat', sans-serif;
  }

  h1 {
  font-size: 16px;
  font-weight: 700;
  color: rgb(95,56,19);
  }

  h3 {
  font-size: 15px;
  font-weight: 700;
  }

  a:hover {
  color: rgb(184, 149, 117);
  text-decoration: none;
  }

  p {
  font-size: 14px;
  line-height: 1.5;
  letter-spacing: .2px;
  }

  .cursor-pointer {
  cursor: pointer;
  }

  .links-marrom {
  color: rgb(184, 149, 117);
  font-weight: bold;
  }
  /* Menu de Navegação */
  nav li {
  margin: 0 25px;
  }

  nav .nav-link {
  color: black;
  font-size: 12px;
  font-weight: 700;
  }

  nav .nav-link:hover {
  color: rgb(166,123,82);
  }

  nav .nav-item.active .nav-link {
  color: rgb(166,123,82);
  }

  nav ul li img {
  border-left: 1px solid grey;
  padding: 8px 32px;
  }

</style>