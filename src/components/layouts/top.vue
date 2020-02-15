<template>
  <nav class="navbar navbar-expand-lg navbar-light box-shadow">
    <div class="container">
      <router-link to="/home" class="navbar-brand">Lung Tung</router-link>
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        Menu
        <i class="navbar-toggler-icon"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link">Posts</a>
          </li>
          <li class="nav-item">
            <a class="nav-link">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
      
</template>

<script>

export default {
  name: 'Header',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  nav {

  }
</style>
