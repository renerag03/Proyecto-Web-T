<template>
  <div class="margen">
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="40000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd">
      <b-carousel-slide>
        <template v-slot:img>
          <img
            class="d-block img-fluid w-100 imagenes-carousel logo-principal"
            width="1024"
            height="480"
            src="@/assets/Pasteleria.png"
            alt="image slot"
          />
      </template>
      </b-carousel-slide>
       <b-carousel-slide>
        <template v-slot:img>
          <img
            class="d-block img-fluid w-100 imagenes-carousel"
            width="1024"
            height="480"
            src="@/assets/Acontecimiento.png"
            alt="image slot"
          />
          <div class="carousel-caption d-none d-md-block">
            <h1 class="text-warning"> <b><em>BIENVENIDOS </em></b></h1>
        <h2 class="text-warning"> <b><em>A Nuestra Pasteleria</em></b></h2>
        <h4 class="colorP2"> <b><em>Tu creas tu torta...
          Con nosotros tu eliges y creas tu torta no
          limitamos tus opciones a un catalogo, los modelos
          que te presentamos solo son para que conozcas nuestro trabajo.</em></b></h4>
      </div>
      </template>
      </b-carousel-slide>
       <b-carousel-slide>
        <template v-slot:img>
            <img
            class="d-block img-fluid w-100 imagenes-carousel"
            width="800"
            height="480"
             src="@/assets/A09.png"
            alt="image slot"
          />
          <div class="carousel-caption d-none d-md-block">
        <h1 class="text-warning"> <b><em>Mis Antojos y Caprichos</em></b></h1>
        <h4 class="text-warning"> <b><em>Tortas para matrimonio</em></b></h4>
        <p></p>
      </div>
        </template>
      </b-carousel-slide>
       <b-carousel-slide>
        <template v-slot:img>
            <img
            class="d-block img-fluid w-100 imagenes-carousel"
            width="800"
            height="480"
             src="@/assets/Angry.png"
            alt="image slot"
          />
          <div class="carousel-caption d-none d-md-block">
        <h1 class="text-warning"><b><em>Mis Antojos y Caprichos</em></b></h1>
        <h4 class="text-warning"><b><em>Tortas para Cumpleaños</em></b></h4>
        <p></p>
      </div>
        </template>
      </b-carousel-slide>
       <b-carousel-slide>
        <template v-slot:img>
          <img
            class="d-block img-fluid w-100 imagenes-carousel"
            width="1024"
            height="480"
            src="@/assets/TortasPersonalizadas.png"
            alt="image slot"
          />
           <div class="carousel-caption d-none d-md-block">
        <h1 class="text-warning"><b><em>Mis Antojos y Caprichos</em></b></h1>
        <h4 class="text-warning"><b><em>Tortas para Cumpleaños</em></b></h4>
        <p></p>
      </div>
        </template>
      </b-carousel-slide>
       <b-carousel-slide>
        <template v-slot:img>
          <img
            class="d-block img-fluid w-100 imagenes-carousel"
            width="1024"
            height="480"
            src="@/assets/TortasNormales.png"
            alt="image slot"
          />
           <div class="carousel-caption d-none d-md-block">
        <h1 class="text-warning"><b><em>Mis Antojos y Caprichos</em></b></h1>
        <h4 class="text-warning"><b><em>Tortas</em></b></h4>
        <p></p>
      </div>
        </template>
      </b-carousel-slide>
    </b-carousel>
   </div>
</template>

<script>
export default {
  data () {
    return {
      slide: 0,
      sliding: null
    }
  },
  methods: {
    onSlideStart (slide) {
      this.sliding = true
    },
    onSlideEnd (slide) {
      this.sliding = false
    }
  }
}
</script>
<style>
.margen {
  background-color: deeppink;
  padding-top: 5px;
  border-top: 2px;
}
.logo-principal{
  background-color: #000;
}
.imagenes-carousel{
  width: 1024px;
  height: 580px ;
}
</style>
