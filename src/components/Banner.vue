<template>
  <!-- Banner Rotativo -->
  <header id="header-banner" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#header-banner" data-slide-to="0" class="active"></li>
      <li data-target="#header-banner" data-slide-to="1"></li>
      <li data-target="#header-banner" data-slide-to="2"></li>
    </ol>

    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="../assets/img/banner.png">
      </div>
      <div class="carousel-item">
        <img src="../assets/img/banner.png">
      </div>
      <div class="carousel-item">
        <img src="../assets/img/banner.png">
      </div>
    </div>
  </header>
</template>

<style>

  #header-banner ol {
    margin-bottom: 50px;
  }

  #header-banner .carousel-indicators li {
    width: 10px;
    height: 10px;
    border: 1px solid white;
    border-radius: 100%;
    margin: 5px 8px;
    background-color: transparent;
  }

  #header-banner .carousel-indicators li.active {
    background-color: white;
  }

</style>