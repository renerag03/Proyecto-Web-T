<template>
  <div class="padre">
  <header class="header margen-interno">
    <div class="menu">
      <div class="logo">
        <a href="#"><img src="@/assets/Pasteleria.png" width="320"></a>
        </div>
      <div class="texto">
            <b-navbar toggleable="lg" type="dark">
        <b-navbar-brand href="#"></b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#"> <router-link to="/"> <i class="fas fa-home"></i> INICIO</router-link> </b-nav-item>
            <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  id="navbarDropdownMenuLink"
                  role="button"
                  data-toggle="dropdown"
                  aria-haspopup="false"
                  aria-expanded="false"
                > <router-link to="/servicios"><i class="fas fa-cart-arrow-down"></i> SERVICIOS </router-link></a>
                <div class="dropdown-menu color"  aria-labelledby="navbarDropdownMenuLink">
                  <b-dropdown-item > <router-link to="/tortas"><i class="fas fa-birthday-cake"></i> TORTAS</router-link> </b-dropdown-item>
                  <b-dropdown-item > <router-link to="/postres"> <i class="fas fa-mortar-pestle"></i> POSTRES</router-link></b-dropdown-item>
                </div>
              </li>
          <b-nav-item href="#"> <router-link to="/galeria"><i class="fas fa-camera-retro"></i> GALERIA</router-link></b-nav-item>
          <b-nav-item href="#"> <router-link to="/contacto"> <i class="fas fa-camera-retro"></i> CONTACTO</router-link></b-nav-item>
          </b-navbar-nav>
          </b-collapse>
      </b-navbar>
        </div>
      <div class="social">
        <div> <router-link to="/celular"><a><i class="fas fa-mobile-alt"></i></a></router-link></div>
        <div><a target="_black" href="https://api.whatsapp.com/send?phone=59179341022"><i class="fab fa-whatsapp"></i></a></div>
        <div><a target="_black" href="https://twitter.com/y_antojos"><i class="fab fa-twitter-square"></i></a></div>
        <div><a target="_black" href="https://www.facebook.com/Pasteler%C3%ADa-Mis-Antojos-y-Caprichos-108913157320536/?modal=admin_todo_tour"><i class="fab fa-facebook-square"></i></a></div>
        <div><a target="_black" href="https://www.messenger.com/login.php?next=https%3A%2F%2Fwww.messenger.com%2Ft%2F108913157320536%2F%3Fmessaging_source%3Dsource%253Apages%253Apage_plugin_message"><i class="fab fa-facebook-messenger"></i></a></div>
      </div>
    </div>
  </header>
</div>
</template>

<script>
export default {

}
</script>

<style>
*{
  margin:0px;
  padding:0px;
  box-sizing: border-box;
}
.padre{
  display: flex;
  flex-flow: column nowrap;
}
.margen-interno{
  padding: 0 50px;
}
    .header{
      background-color: #000;
      display: flex;
      flex-flow: column nowrap;
    }
        .menu{
          display: flex;
          flex-flow: row nowrap;
          height:auto;
          align-items: center;
        }
            .logo{
              flex: 2 1 auto;
            }
            .texto{
              flex:4 1 auto;
              font-size: 18px;
              padding: 0 10px;
              letter-spacing: 2px
            }
            .texto a :hover{
              color:indigo;
            }
                .texto a{
                  text-decoration: none;
                  color:deeppink;
                }
            .social{
              display: flex;
              flex:1 1 auto;
              letter-spacing: 10px;
            }
              .social a{
                font-size: 18px;
                color: #fff;
                padding: 0 5px
              }
              .social a:hover{
                color: deeppink;
              }
              @media all and (max-width: 800px){
  .menu{
    flex-direction: column;
    height: auto;
  }
}
.color{
  background-color:#000;
}
</style>
