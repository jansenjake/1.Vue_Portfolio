<template>
    
    <!-- <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <router-link><a class="nav-link active" aria-current="page" href="#">Home</a></router-link>
        <router-link><a class="nav-link" href="#">About</a></router-link>
        <router-link><a class="nav-link" href="#">Resume</a></router-link>
        <router-link><a class="nav-link" href="#" >Projects</a></router-link>
        <router-link><a class="nav-link" href="#" >Testimonials</a></router-link>
        <router-link><a class="nav-link" href="#" >Contacts</a></router-link>
    </div>
    </div>
  </div>
</nav> -->

    <nav class="MyNav">
        <!-- <a class="navbar-brand">Nav</a> -->
<ul>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About Me</router-link> |
    <router-link to="/resume">Resume</router-link> |
    <router-link to="/projects">Projects</router-link> |
    <router-link to="/testimonials">Testimonials</router-link> |
    <router-link to="/contact">Contact Me</router-link> 
</ul>
    </nav>

</template>

<script>
export default{
    name: 'NavBar',
}




</script>

<style>

.MyNav{
  position: relative;
  top: 0;
  left: 0;
  width: 100%;
 
}



</style>