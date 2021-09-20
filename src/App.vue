<template>
  <div id="app">
   
     <header>
        <div class="navbar navbar-dark bg-dark box-shadow">
          <div class="container d-flex justify-content-start">
            <a href="#" class="navbar-brand d-flex align-items-center">
              <!-- <img src="./assets/logo.png"> -->
              <strong>Article App</strong>
            </a>
             <a href="#" class="navbar-brand d-flex align-items-center">  <router-link to='/'>Home</router-link></a>
              <router-link :to="{name: 'articles'}">Articles</router-link>
          
          </div>
        </div>
      </header>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
