<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light box-shadow">
      <div class="container">
        <a class="navbar-brand">Tập Tành Blog</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="navbar-toggler-icon"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#">Game</a>
            </li>
            <li class="nav-item">
              <a class="nav-link">Lập trình</a>
            </li>
            <li class="nav-item">
              <a class="nav-link">Phim ảnh</a>
            </li>
            <li class="nav-item">
              <a class="nav-link">Liên hệ</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <header class="masthead" style="background-image: url('https://blackrockdigital.github.io/startbootstrap-clean-blog-jekyll/img/bg-index.jpg')">
      <div class="overlay"></div>
      <div class="container">
        <div class="row">
          <div class="col-lg-8 col-md-10 mx-auto">
            <div class="page-heading">
              <h1>Clean Blog</h1>
            </div>
          </div>
        </div>
      </div>
    </header>
  </div>
      
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
