<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
 
 <nav>
  <RouterLink to="/">Personal</RouterLink>
  <RouterLink to="/skill">Skill</RouterLink>      
 </nav>

 <header>
  <div class="container">
    
    <img alt="Vue logo" class="logo" src="@/assets/pp2.jpeg" width="300" height="300" />

    <div class="wrapper">
      <HelloWorld msg="My name is Bagus wicaksana."/>
    </div>
  </div>
    
  </header>

  

  <RouterView />

  <footer>
    <p>Copyright © 2022 Bagus Wicaksana. All right reserved.</p>
  </footer>
  
</template>

<style scoped>
footer{
  width: 100%;
  height: 150px;
  background-color: gainsboro;
  text-align: center;
}

p{
  padding-top: 50px;
}

header {
  line-height: 1.5;
  /* max-height: 100vh; */
  margin-bottom: 240px;
}



/* .logo {
  display: block;
  margin: 0 auto 2rem;
} */

nav {
  width: 100%;
  height: 70px  ;
  /* margin-bottom: 90px; */
  /* justify-content: center ; */
  /* position: fixed; */
  background-image: linear-gradient( 174.2deg,  rgba(255,244,228,1) 7.1%, rgba(240,246,238,1) 67.4% );
  }

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
  margin-top: 5px;
}

nav a:first-of-type {
  border: 0;
}

/* @media (min-width: 1024px) { */
  header {
    display: flex;
    place-items: left;
    padding-right: calc(var(--section-gap) / 1);
  }

  .logo {
    margin-top: 70px;
    margin-left: 20px;
    border-radius: 200px;
    margin-right: 50px;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: center;
    font-size: 1rem;
    padding: 1rem 0;
    /* margin-top: 1rem; */
  }
  .container{
    margin-top: 100px;
    margin-left: 200px;
    display: flex;
  }
</style>
