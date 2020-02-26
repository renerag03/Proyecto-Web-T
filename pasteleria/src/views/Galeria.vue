<template>
  <div class="margenG">
    <div class="margenG2">
      <div class="fondoG">
  <b-container fluid class="p-4 colorG text-white" >
  <h1 class="text-warning text-center"> <b><em>GALERIA DE FOTOS </em></b></h1>
  <br>
  <b-row class="text-white">
    <b-col cols="12" sm="6" md="4" lg="4">
     <router-link to="/eventos"> <img src="@/assets/Acontecimiento.png" alt="..." class="img-thumbnail imgG"></router-link><br>
      <br>
      <h3 class="text-warning text-center"> <b><em>Tortas para Eventos</em></b></h3>
      <router-link to="/eventos" class="boton"><button type="button" class="btn btn-outline-danger text-justify"> <em>Ver mas</em></button></router-link>
    </b-col>
    <b-col cols="12" sm="6" md="4" lg="4">
     <router-link to="/personalizadas"><img src="@/assets/Unicornio.png" alt="..." class="img-thumbnail imgG1"></router-link><br>
     <br>
     <h3 class="text-warning text-center"> <b><em>Tortas Personalizadas</em></b></h3>
     <router-link to="/personalizadas" class="boton"><button type="button" class="btn btn-outline-warning"> <em>Ver mas</em></button></router-link>
    </b-col>
    <b-col cols="12" sm="6" md="4" lg="4">
     <router-link to="/normales"><img src="@/assets/TortasNormales.png" alt="..." class="img-thumbnail imgG2"></router-link><br>
     <br>
     <h3 class="text-warning text-center"> <b><em>Tortas</em></b></h3>
     <router-link to="/normales" class="boton"><button type="button" class="btn btn-outline-success"> <em>Ver mas</em></button></router-link>
    </b-col>
  </b-row>
</b-container>
</div>
</div>
  </div>
</template>

<script>

export default {
}
</script>

<style>
.margenG {
  background-color: deeppink;
  padding-top: 5px;
  border-top: 2px;
}
.margenG2 {
  background-color: indigo;
  padding-bottom: 5px;
  border-bottom: 2px;
}
.fondoG {
  background-color: black;
}
</style>
