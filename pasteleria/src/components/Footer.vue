<template>
  <footer class="footer margen-interno">
      <div class="logo-f">
        <a href="#"><img src="@/assets/Pasteleria.png" width="320"></a>
      </div>
      <div class="texto-f">
         <b-col>
          <br />
          <h3 class="text-light text-center"> <b><em class="text-warning"> Tortas a pedido</em></b></h3>
          <h6
            class="text-warning">
            <em> Te ofrecemos nuestro servicio para poder cumplir tus espectativas para ese dia tan esperado y sea un recuerdo especial en tu vida </em></h6>
          <div class="text-center">
            <b-spinner variant="danger" label="Spinning"></b-spinner>
            <b-spinner variant="danger" type="grow" label="Spinning"></b-spinner>
            <b-spinner variant="warning" label="Spinning"></b-spinner>
            <b-spinner variant="warning" type="grow" label="Spinning"></b-spinner>
            <b-spinner variant="success" label="Spinning"></b-spinner>
            <b-spinner variant="success" type="grow" label="Spinning"></b-spinner>
          </div>
        </b-col>
      </div>
      <div class="social-f">
       <div> <router-link to="/celular"><a><i class="fas fa-mobile-alt"></i></a></router-link></div>
        <div><a target="_black" href="https://api.whatsapp.com/send?phone=59179341022"><i class="fab fa-whatsapp"></i></a></div>
        <div><a target="_black" href="https://twitter.com/y_antojos"><i class="fab fa-twitter-square"></i></a></div>
        <div><a target="_black" href="https://www.facebook.com/Pasteler%C3%ADa-Mis-Antojos-y-Caprichos-108913157320536/?modal=admin_todo_tour"><i class="fab fa-facebook-square"></i></a></div>
        <div><a target="_black" href="https://www.messenger.com/login.php?next=https%3A%2F%2Fwww.messenger.com%2Ft%2F108913157320536%2F%3Fmessaging_source%3Dsource%253Apages%253Apage_plugin_message"><i class="fab fa-facebook-messenger"></i></a></div>
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
.footer{
      background-color:#000;
      display: flex;
      flex-flow: row nowrap;
      align-items: center;
}
        .logo-f{
              flex: 1 1 auto;
        }
        .texto-f{
              flex:1 1 auto;
        }
          .texto-f h6{
            width: 100%;
            text-justify:center;
            text-align:center;
            padding:0px 100px;
          }
      .social-f{
        display: flex;
        flex:1 1 auto;
        letter-spacing: 15px;
      }
          .social-f a{
            font-size: 20px;
            color: #fff;
            padding: 0 5px
          }
          .social-f a:hover{
            color: indigo;
          }

</style>
