<template>
  <v-app>
    <div class="container">
      <v-img style="width: 100%;" src="../public/img/header-background.jpeg"></v-img>
      <div class="centered">
        <h1>Groupe Touzel Leger inc <sub style="color: orange;">work in progress</sub></h1>
      </div>
    </div>
    <ul class="navbar">
      <li class="nav-item">Documents&nbsp;&nbsp;<v-icon>mdi-archive</v-icon></li>
      <li class="nav-item">Zonage&nbsp;&nbsp;<v-icon>mdi-compass</v-icon></li>
      <li class="nav-item">Services&nbsp;&nbsp;<v-icon>mdi-cards-spade</v-icon></li>
      <li class="top-nav-icon"><v-img class="top-icon" src="../public/img/logo-rounded.jpg"></v-img></li>
    </ul>
    <HomePage/>
  </v-app>
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',

  components: {
    HomePage,
  },

  data: () => ({
    //
  }),
}
</script>

<style>
  h1, h2, h3, h4, h5, h6 {
    font-size: 1.5vw;
    color: rgb(23, 23, 136);
  }
  .navbar {
    position: fixed;
    top: 0;
    height: auto;
    background-color: white;
    width: 100vw;
    list-style-type: none;
    z-index: 2;
    padding: 1vw;
    padding-right: 3vw;
    box-shadow: 0 5px 5px rgba(0, 0, 0, 0.2);
  }
  li {
    float: right;
    margin: 0 10px 0 10px;
    font-size: 1.3vw;
  }
  .top-nav-icon {
    float: left;
    cursor: pointer;
  }
  .nav-item {
    padding: 0.5vw;
    border-radius: 10px;
    cursor: pointer;
  }
  .nav-item:hover
  {
    background-color: rgba(0, 0, 0, 0.2);
  }
  .text {
    font-size: 1.2vw;
  }
  .col{
    text-align: center;
  }
  .container {
    position: relative;
    text-align: center;
    color: white;
  }
  .centered {
    position: absolute;
    width: 30vw;
    top: 50%;
    left: 35vw;
  }
  .top-icon {
    width: 3vw;
  }
</style>