<template>
  <div class="margenN">
    <div class="margenN2">
      <div class="fondoN">
      <b-container fluid class="p-4">
        <h1 class="text-warning text-center"> <b><em>TORTAS</em></b></h1><br>
  <b-row>
    <b-col>
     <img src="@/assets/Tortas/N01.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N02.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N03.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>=
  </b-row>
</b-container>
<b-container fluid class="p-4">
  <b-row>
    <b-col>
     <img src="@/assets/Tortas/N04.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N05.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N06.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>=
  </b-row>
</b-container><b-container fluid class="p-4">
  <b-row>
    <b-col>
     <img src="@/assets/Tortas/N07.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N08.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N09.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>=
  </b-row>
</b-container>
<b-container fluid class="p-4 bg-dark">
  <b-row>
    <b-col>
     <img src="@/assets/Tortas/N10.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N11.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N12.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>=
  </b-row>
</b-container><b-container fluid class="p-4">
  <b-row>
    <b-col>
     <img src="@/assets/Tortas/N13.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N14.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N15.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>=
  </b-row>
</b-container>
<b-container fluid class="p-4">
  <b-row>
    <b-col>
     <img src="@/assets/Tortas/N16.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N17.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
    <b-col>
      <img src="@/assets/Tortas/N18.jpg" alt="..." class="img-thumbnail fotoN">
    </b-col>
  </b-row>
</b-container>
<div class="regresar">
  <router-link to="/galeria"><b-button block variant="warning"><b><em> REGRESAR </em></b></b-button></router-link>
</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.margenN{
background-color: deeppink;
padding-top: 5px;
border-top: 2px;
}
.margenN2{
background-color: indigo;
padding-bottom: 5px;
border-bottom: 2px;
}
.fondoN{
  background-color: black;
}
    .fondoN a{
      text-decoration: none;
    }
.fotoN{
  background-color: yellow;
  border-radius: 20%;
  border: 2px;
  width: 400px;
  height: 350px;
}
.regresar{
  padding:20px 600px;
  border: 3px;
}

</style>
