<template>
  <div id="app">
    <div class="container">
      <ul class="nav justify-content-center">
        <li class="nav-item">
          <router-link to="/" class="nav-link active" >Home</router-link> 
        </li>
        <li class="nav-item">
          <router-link to="/products" class="nav-link">Products</router-link> 
        </li>
        <li class="nav-item">
          <router-link to="/contact" class="nav-link">Contact</router-link> 
        </li>
        <li class="nav-item">
          <router-link to="/users" class="nav-link">User</router-link> 
        </li>
        <li class="nav-item">
          <router-link to="/about" class="nav-link">About</router-link> 
        </li>
        <li class="nav-item">
          <router-link to="/login" class="nav-link">Login</router-link> 
        </li>
      </ul>
      <nav class="nav">


      </nav>
    </div>
    <router-view/>
  </div>
</template>

<style>
  @import "../node_modules/bootstrap/dist/css/bootstrap.min.css";
  body{
    background-color: #F2F2F2;
  }
  /* #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }

  #nav {
    padding: 30px;
  }

  #nav a {
    font-weight: bold;
    color: #2cfe5;
  }

  #nav a.router-link-exact-active {
    color: #42b983;
  } */
</style>
