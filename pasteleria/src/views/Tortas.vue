<template>
  <div class="margenT">
    <div class="margenT2">
    <div class="fondoT">
    <br />
      <h1 class="texto2 text-center"><b> <em> HAS TU PEDIDO </em></b></h1>
      <br />
      <div class="container">
        <div class="card mb-3 torta">
          <div class="row no-gutters tortaT">
            <div class="col-md-4 torta">
              <img src="@/assets/TresLeches.jpg" class="card-img" alt="..." />
            </div>
            <div class="col-md-8 bg-warning texts">
              <div class="card-body">
                <h2 class="card-title text-danger"> <em class="texto1"> <b> TORTA DE TRES LECHES </b></em></h2>
                <ul class="card-text text-dark text-justify" >
                  <li> <h4> <b> <em>- Masa de vainilla con un toque de limon</em></b></h4></li>
                  <li> <h4> <b> <em>- Relleno de crema y manjar</em></b></h4></li>
                  <li> <h4> <b> <em>- Decorado de Crema con Manjar </em></b></h4></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="card mb-3 torta">
          <div class="row no-gutters">
            <div class="col-md-8 bg-warning">
              <div class="card-body">
                <h2 class="card-title text-danger texts"> <em> <b> TORTA DE FRUTILLA </b></em></h2>
                <ul class="card-text text-dark text-justify">
                  <li> <h4> <b> <em>- Masa de frutilla</em></b></h4></li>
                  <li> <h4> <b> <em>- Relleno de crema con salsa frutilla</em></b></h4></li>
                  <li> <h4> <b> <em>- Decorado con fruta y chocolate</em></b></h4></li>
                </ul>
              </div>
            </div>
            <div class="col-md-4 torta">
              <img src="@/assets/Frutilla.jpg" class="card-img" alt="..." />
            </div>
          </div>
        </div>
        <div class="card mb-3 torta">
          <div class="row no-gutters">
            <div class="col-md-4 torta">
              <img src="@/assets/Postres00.png" class="card-img" alt="..." />
            </div>
            <div class="col-md-8 bg-warning">
              <div class="card-body">
                <h2 class="card-title text-danger texts"> <em> <b> TORTA DE CHOCOLATE</b></em></h2>
                <ul class="card-text text-dark text-justify">
                  <li> <h4><b> <em>- Masa de chocolate</em></b></h4></li>
                  <li> <h4> <b> <em>- Relleno de crema con ganache de cocholate</em></b></h4></li>
                  <li> <h4> <b> <em>- Decorado con bombones, chocolate blanco y ganache</em></b></h4></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="card mb-3 torta">
          <div class="row no-gutters">
            <div class="col-md-8 bg-warning">
              <div class="card-body">
                <h2 class="card-title text-danger texts"> <em> <b> TORTA DE MOKA</b></em></h2>
                <ul class="card-text text-dark text-justify">
                  <li> <h4> <b> <em>- Masa de moka</em></b></h4></li>
                  <li> <h4> <b> <em>- Relleno de queso crema y dulce de leche</em></b></h4></li>
                  <li> <h4> <b> <em>- Decorado con crema de moka y ganache de chocolate</em></b></h4></li>
                </ul>
              </div>
            </div>
            <div class="col-md-4 torta">
              <img src="@/assets/Moka.jpg" class="card-img" alt="..." />
            </div>
          </div>
        </div>
      </div>
      <br>
    </div>
     </div>
    </div>
</template>

<script>
export default {}
</script>

<style>
.margenT{
background-color: deeppink;
padding-top: 5px;
border-top: 2px;
}
.margenT2{
background-color: indigo;
padding-bottom: 5px;
border-bottom: 2px;
}
.fondoT{
  background-color: black;
}
.torta{
  background-color: deeppink;
  padding: 5px;
  border: 2px
}
.texto2{
  color: yellow
}
ul {
  list-style: none;
}
.texts{
  text-align:center;
}
</style>
