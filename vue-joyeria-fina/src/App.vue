<template>
  <div id="app">

    <!--   HEADER   -->

    <header>
      <div class="menu">
        <div class="ed-grid s-grid-7 m-grid-7 lg-grid-12 ul">
          <div class="s-x-3 s-cols-3 s-main-center s-cross-center lg-cols-2 lg-x-1 lg-main-start lg-cross-center"><img src="./assets/img/logo_menu.png" alt="logo-joyera-fina"></div>
          <div class="s-x-1 s-y-1 lg-x-10 lg-main-end lg-cross-center"><a href="#" class="options-menu">Inicio</a></div>
          <div class="s-x-2 s-y-1 lg-x-11 lg-main-center lg-cross-center"><a href="#" class="options-menu">Tienda</a></div>
          <div class="s-x-6 s-cols-2 s-cross-center s-main-center m-x-6 m-cols-2 lg-x-12 lg-main-center lg-cross-center icon flex">
            <a href="#" id="facebook"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-whatsapp"></i></a>
          </div>
        </div>
      </div>
    </header>

    <!--   SECTION 1   -->

    <section class="section1">
      <div class="banners">
        x
      </div>
    </section>

    <!--   SECTION 2   -->

    <section class="section2">
      <div class="ed-grid lg-grid-5 character-1">
        <div class="lg-x-2 ed-grid lg-grid-2 lg-gap-1">
          <div class="img-character flex">
            <img src="./assets/img/icono_pagos.png" alt="img-pagos">
          </div>
          <div>
            <h1 class="title-style-1">Pagos</h1>
            <h2 class="title-style-2">Lorem Ipsum</h2>
          </div>
        </div>
        <div class="lg-x-3 ed-grid lg-grid-2 lg-gap-1">
          <div class="img-character flex">
            <img src="./assets/img/iconos_Envios.png" alt="img-envios">  
          </div>
          <div>
            <h1 class="title-style-1">Envios</h1>
            <h2 class="title-style-2">Lorem Ipsum</h2>
          </div>
        </div>
        <div class="lg-x-4 ed-grid lg-grid-2 lg-gap-1">
          <div class="img-character flex" >
            <img src="./assets/img/icono_productos.png" alt="img-productos">
          </div>
          <div>
            <h1 class="title-style-1">Productos</h1>
            <h2 class="title-style-2">Lorem Ipsum</h2>
          </div>
        </div>
      </div>
    </section>

    <!--   SECTION 2 CAROUSEL   -->

    <section class="section2-carousel">
      <div class="ed-grid s-grid-1 section2-responsive">
        <section2carousel></section2carousel>
      </div>
    </section>

    <!--   SECTION 3   -->

    <section class="section3">
      <div class="ed-grid s-grid-1 lg-grid-5 sec-3 lg-gap-0">
        <div class="s-y-2 s-cross-center s-main-center lg-x-1 lg-cols-3 lg-y-2 lg-main-center lg-cross-center sec-left-3">
          <img src="./assets/img/logo_llamado_a_la_acción.png" alt="icono-tienda" width="10%">
          <p class="p-sec-3">‘’Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.’’</p>
          <a href="#">IR A LA TIENDA</a>
        </div>
        <div class="s-x-1 s-y-1 lg-x-4 lg-cols-2 lg-rows-3 flex img-tienda">
          <img src="./assets/img/chica_llamado_acción.png" alt="img-tienda">
        </div>
      </div>
    </section>

    <!--   SECTION 4   -->

    <section class="section4">
      <div>
        <div class="separator">
          <img src="img/separador_secciones.png" alt="">
        </div>
        <div class="sec-4-div">
          <h2>Productos Destacados</h2>
           <products></products>
        </div>
      </div>
    </section>
     
      <!--   SECTION 5   -->

      <section class="section5">
        <div class="ed-grid s-grid-3 lg-grid-5 lg-gap-0 sec-5-div">
          <div class="s-x-1 s-y-1 s-cols-2 s-rows-2 lg-x-1 lg-y-1 lg-rows-2 lg-cols-5 sec-5-1 lg-cross-center">
            <img src="./assets/img/hoja_llamado_accion2.png" alt="hoja-llamado-a-la-accion">
          </div>
          <div class="s-x-1 s-y-2 s-cols-3 lg-x-1 lg-y-2 lg-cols-5 lg-main-center -lg-cross-center sec-5-2">
            <p align="center">‘’Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.’’</p>
          </div>
        </div>
      </section>

      <!--   FOOTER   -->

      <footer>
        <div class="flex">
          <img src="./assets/img/logo_Footer.png" alt="logo-footer">
        </div>
      </footer>

      <!--   BUTTON WHATSAPP   -->

      <a href="#" class="whatsapp-float"><i class="fab fa-whatsapp"></i></a>

    </div>
  </template>

  <script>
  import banners from './components/banners.vue';
  import section2carousel from './components/section2Carousel.vue'
  import products from './components/products.vue'

  export default {
    name: 'App',
    components: {
      banners,
      section2carousel,
      products
    },
  };
  </script>

  <style>
  @import './assets/css/style.css';
  @import './assets/css/ed-grid.min.css';


  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 0;
  }
  button{
    outline:none;
  }

  </style>
