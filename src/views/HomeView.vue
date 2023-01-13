<template>
  <h1 class="HomeHead">Portfolio <h1 class="of">Of</h1> <h1 class="name">Jake Jansen</h1></h1>
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
  animation: top-down 2s ease-out;
  font-size: 3rem;
  color:black;
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

.of {
  font-size: 3rem;
  animation: of 3s ease-in-out;
}

@keyframes of {
  0%{
    transform: translateX(-100%)
    
  }
  100%{
    transform: translateX(0%)
  }
}

.name{
  font-size: 4rem;
  color: black;
  animation: down-up 3.5s ease-in-out
}

@keyframes down-up{
  0%{
    transform: translateY(-100%);
  }
  100%{
    transform: translateY(0%);
  }
}


</style>
