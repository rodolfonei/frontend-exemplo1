<template>
  <section id="section-parceiros" class="p-5 carousel slide" data-ride="carousel">
    <div class="container d-flex flex-column align-items-center justify-content-center">
      <h1 class="mb-5">PARCEIROS</h1>
      <ol class="carousel-indicators">
        <li data-target="#section-parceiros" data-slide-to="0" class="active"></li>
        <li data-target="#section-parceiros" data-slide-to="1"></li>
      </ol>

      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="row text-center">
            <div class="col my-4"><img src="../assets/img/parceiro1.png"></div>
            <div class="col my-4"><img src="../assets/img/parceiro2.png"></div>
            <div class="col my-4"><img src="../assets/img/parceiro3.png"></div>
            <div class="col my-4"><img src="../assets/img/parceiro4.png"></div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="row text-center">
            <div class="col my-4"><img src="../assets/img/parceiro1.png"></div>
            <div class="col my-4"><img src="../assets/img/parceiro2.png"></div>
            <div class="col my-4"><img src="../assets/img/parceiro3.png"></div>
            <div class="col my-4"><img src="../assets/img/parceiro4.png"></div>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>

<style>

  #section-parceiros {
    background-color: rgb(244,244,244);
  }

  #section-parceiros .carousel-indicators li {
    width: 10px;
    height: 10px;
    border: 1px solid rgb(166,123,82);
    border-radius: 100%;
    margin: 5px;
    background-color: transparent;
  }

  #section-parceiros .carousel-indicators li.active {
    background-color: rgb(166,123,82);
  }

</style>