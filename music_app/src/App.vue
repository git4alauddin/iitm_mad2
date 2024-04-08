<template>
  <div id="app">
    
    <hr>
    <h3>navbar_comp</h3>
    <Navbar />
    <hr>
    <br>
    
    <hr>
    <h3>register_comp</h3>
    <Register />
    <hr>
    <br>

    <hr>
    <h3>login_comp</h3>
    <Login />
    <hr>
    <br>

    <hr>
    <h3>footer_comp</h3>
    <Foot />
    <hr>
    <br>

  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Foot from './components/Foot.vue'
import Register from './components/Register.vue'
import Login from './components/Login.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Foot, 
    Register,
    Login,
   
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
