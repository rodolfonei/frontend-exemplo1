<template>
  <section id="section-sobre-noticias" class="container d-flex flex-wrap align-items-start justify-content-between py-5 px-0">
      <img class="img-fluid col-12 col-md-3" src="../assets/img/sobre1.png">
      <!-- Sobre -->
      <div class="col-12 col-md-5">
        <h1>SOBRE A BAKERY</h1>
        <p>Ut vitae volutpat risus. Nam vitae congue odio, mattis dignissim neque. Nam eros sapien, semper in pellentesque ut, suscipit eu nunc. Donec malesuada egestas ligula, non malesuada sapien suscipit ut.</p><br>
        <p>Praesent sed ipsum ullamcorper purus scelerisque laoreet. Nulla lobortis ex eu mi accumsan, non hendrerit ex rhoncus. Etiam auctor libero porttitor tellus imperdiet consequat. Nam porttitor diam in eleifend fringilla.</p>
        <a class="links-marrom" href="#">Conheça mais</a>
        <img src="../assets/img/seta.png" alt="">
      </div>
      <!-- Notícias -->
      <aside id="aside-noticias" class="col-12 col-md-4">
        <h1>ÚLTIMAS NOTÍCIAS</h1>
        <a :key="noticia.id" v-for="noticia in noticias"  href="#">
          <p class="links-marrom">{{ noticia.date }}</p>
          <p class="p-noticia">{{ noticia.texto }}</p>
          <hr>
        </a>
        <div class="text-right">
          <a class="links-marrom" href="#">Lista completa</a>
          <img src="../assets/img/seta.png" alt="">
        </div>
      </aside>
    </section>
</template>

<style>

  #section-sobre-noticias > * {
    padding: 40px 30px;
  }

  #section-sobre-noticias h1 {
    margin-bottom: 18px;
  }

  /* Notícias */
  aside {
    background-color: rgb(244,244,244);
  }

  aside h1 {
    color: rgb(209,187,166);
  }

  .p-noticia {
    color: black;
  }

</style>

<script>

  export default {
    data() {
      return {
        noticias: [
          {
            id: 1,
            date: "26/08/2019",
            texto: "Nulla commodo lorem at elit scelerisque mollis. Maecenas et libero sed purus"
          },
          {
            id: 2,
            date: "26/08/2019",
            texto: "Nulla commodo lorem at elit scelerisque mollis. Maecenas et libero sed purus"
          },
          {
            id: 3,
            date: "26/08/2019",
            texto: "Nulla commodo lorem at elit scelerisque mollis. Maecenas et libero sed purus"
          }
        ]
      }
    }
  }

</script>