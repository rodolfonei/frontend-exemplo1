<template>
  <section id="section-produtos" class="container d-flex flex-wrap flex-lg-nowrap justify-content-center">
    <figure v-for="produto in produtos" >
      <div :key="produto.id" class="div-img-produtos">
        <img class="img-fluid" :src="produto.url">
      </div>
      <figcaption>{{ produto.nome.toUpperCase() }}</figcaption>
    </figure>
  </section>
</template>

<style>

  #section-produtos {
    margin-top: -45px;
    position: relative;
    z-index: 99;
  }

  .div-img-produtos {
    background: linear-gradient(to top, rgba(0,0,0,0.5), rgba(244,244,244,0.7));
  }

  .div-img-produtos:hover {
    background: none;
  }

  #section-produtos img {
    position: relative;
    z-index: -1;
  }

  #section-produtos figcaption {
    font-size: 18px;
    color: white;
    font-weight: bolder;
    text-align: center;
    position: relative;
    z-index: -1;
    bottom: 40px;
  }

</style>

<script>

import produto1 from '../assets/img/produto1.png'
import produto2 from '../assets/img/produto2.png'
import produto3 from '../assets/img/produto3.png'
import produto4 from '../assets/img/produto4.png'
import produto5 from '../assets/img/produto5.png'

export default {
  data() {
    return {
      produtos: [
        {
          id: 1,
          nome: "curabitur",
          url: produto1
        },
        {
          id: 2,
          nome: "faucibus",
          url: produto2
        },
        {
          id: 3,
          nome: "ullamcorper",
          url: produto3
        },
        {
          id: 4,
          nome: "duis libero",
          url: produto4
        },
        {
          id: 5,
          nome: "pellentesque",
          url: produto5
        }
      ]
    }
  }
}

</script>