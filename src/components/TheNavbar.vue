<template>
  <div class="container"> 
    <nav class="my-nav navbar navbar navbar-expand-sm bg-dark fixed-top rounded-bottom">
        <div class="navbar-brand nav-title">
          <img class="mr-3" height="40" width="60" src="@/assets/imgs/cee-logo-branco.png" alt="CEE">
          Centro Acadêmico de Engenharia Elétrica e Computação
        </div>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <button class="btn btn-outline-light btn-sm mx-2"><a href="#header" class="nav-link"> O CEE</a></button>
          </li>
          <li class="nav-item">
            <button class="btn btn-outline-light btn-sm mx-2"><a href="" class="nav-link">Senec</a></button>
          </li>
          <li class="nav-item">
            <button class="btn btn-outline-light btn-sm mx-2"><a href="" class="nav-link">Gestão</a></button>
          </li>
          <li class="nav-item">
            <button class="btn btn-outline-light btn-sm mx-2"><a href="" class="nav-link">Contato</a></button>
          </li>
        </ul>
    </nav>
  </div>


</template>


<script>
export default {
  name: 'TheNavbar'
}
</script>


<style scoped>
  @font-face {
    font-family: 'NexusLight';
    src: url('/assets/fonts/Nexa_Light.otf');
  }

    .nav-title {
      font-family: 'NexusLight';
    }

    .my-nav {

    background: linear-gradient(to bottom,rgb(19, 28, 43) 0%, rgb(35, 36, 66) 98%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
    }
    
    .container {
        color:white;
    }

    a {
        text-decoration: none;
        color:white;
    }

    .btn:hover {
      background-color: gray;
    }


</style>
