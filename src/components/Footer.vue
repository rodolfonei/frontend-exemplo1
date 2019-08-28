<template>

  <footer>
    <!-- Flex do Footer -->
    <div class="container d-flex flex-column py-5">
      <!-- Flex dos Logos, Menu, Contato e Local -->
      <div class="d-flex flex-wrap justify-content-between">
        <!-- Logo e Social Media -->
        <div class="d-flex flex-column align-items-center col-12 col-md-4 footer-border">
          <img src="../assets/img/logo.png" alt="Logo">
          <img class="my-4 cursor-pointer" src="../assets/img/social-media.png" alt="Redes Sociais">
        </div>
        <!-- Menu -->
        <div class="d-flex flex-column align-items-center align-items-md-start col-12 col-md-2 footer-border py-2">
          <a href="#">HOME</a>
          <a href="#">SOBRE</a>
          <a href="#">RECEITAS</a>
          <a href="#">NOTÍCIAS</a>
          <a href="#">CONTATO</a>
        </div>
        <!-- Contato e Localização -->
        <div class="d-flex flex-column flex-wrap align-items-start col-12 col-md-5 py-2">
          <!-- Contato -->
          <div class="d-flex align-items-start">
            <img class="my-1 mx-3" src="../assets/img/icon-contato.png" alt="Contato">
            <div>
              <h3 class="d-inline-block">CONTATO</h3>
              <p>(99) 9999-9999 | (99) 99999-9999</p>
            </div>
          </div>
          <!-- Localização -->
          <div class="d-flex align-items-start">
            <img class="my-1 mx-3" src="../assets/img/icon-local.png" alt="Localização">
            <div>
              <h3 class="d-inline-block">LOCALIZAÇÃO</h3>
              <p>Nam porttitor diam in eleifend fringilla, 3180</p>
            </div>
          </div>
        </div>
      </div>
      <!-- Créditos -->
      <div class="d-flex justify-content-between align-items-center mt-5">
        <p id="creditos" class="mx-5">(c) Bakery 2017. Todos direitos reservados.</p>
        <img class="mx-3 cursor-pointer" src="../assets/img/logo-ow.png" alt="">
      </div>
    </div>
  </footer>

</template>

<style>

  footer {
    color: white;
    background-color: rgb(64,50,37);
  }

  footer a {
    color: white;
    padding: 5px 0;
  }

  .footer-border {
    border-bottom: 1px solid rgb(112,101,92);
  }

  #creditos {
    color: rgb(112,101,92);
  }
  /* Media Querie de Tablets para cima */
  @media (min-width: 768px) {
    #section-produtos {
      margin-top: -85px;
    }

    .footer-border {
      border-right: 1px solid rgb(112,101,92);
      border-bottom: none;
    }

    #header-banner img {
      height: auto;
      width: 100%;
    }

    #header-banner ol {
      margin-bottom: 100px;
    }

  }

</style>