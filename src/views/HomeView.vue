<template>
  <h1 class="HomeHead">Portfolio Of Jake Jansen</h1>
  <div class="home">



  </div>

  
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style>

.HomeHead{
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  animation: top-down 3s ease-out;
  font-size: 3rem;
}

@keyframes top-down {
  from{
    transform: translateY(-100%);
    opacity: 0;
    color: rgb(153, 0, 17);

  }
  to{
    transform: translateY(0);
    opacity: 1;
    color: black;
  }
  
}


</style>
