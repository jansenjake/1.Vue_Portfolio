<template>
  <NavBar />
  <div>
  <router-view/>
</div>
<Footer />
</template>

<script>
import NavBar from '../src/components/NavBar.vue'
import Footer from '../src/components/footer.vue'
 export default{
  name: 'App',
  components: {NavBar,Footer}
 }


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
}

nav {
  padding: 30px;
  background-color: rgb(206, 191, 191);
}




nav a {
  font-weight: bold;
  color: rgb(153, 0, 17);
  padding-right: 10px;
  padding-left: 10px;
  padding-bottom: 5px;
  padding-top: 5px;
}

nav a.router-link-exact-active {
  color: black;
}
nav a:hover {
  background-color:rgb(153, 0, 17) ;
  border-radius: 5px;
  transition: 0.5s ease;
}

body{
  background-image: linear-gradient(to right,rgb(153, 0, 17), pink, blue );
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;
  padding-bottom: 100px;
}


</style>
