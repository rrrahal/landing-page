<template>
  <div id="app">
    <the-navbar></the-navbar>
    <the-header> </the-header>
    <the-senec> </the-senec>
  </div>
</template>

<script>
import TheNavbar from './components/TheNavbar'
import TheHeader from './components/TheHeader'
import TheSenec from './components/TheSenec'

export default {
  name: 'app',
  components: {
    TheNavbar,
    TheHeader,
    TheSenec
  }
}
</script>

<style>


#app {

  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
