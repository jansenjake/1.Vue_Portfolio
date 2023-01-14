<template>
    <h1 class="pro"> My Projects</h1>
    <!-- https://boujeebirds.netlify.app -->
    <!-- https://jansenjakeportfolio.netlify.app    p1 -->
    <!-- https://jake-calculator.netlify.app -->


<div class="contain">
  <div class="card" style="width: 18rem;">
  <img src="https://i.postimg.cc/gJVvzCXk/project1.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">My First Ever Project</h5> 
    <p class="card-text"></p>
  </div>
  <div class="card-body">
    <a href="https://jansenjakeportfolio.netlify.app" class="card-link"><button class="see">View</button></a>
  </div>
</div>
<h3>
  Project Name: Jake Jansen Portfolio
</h3>
</div>

<div class="contain">
<div class="card" style="width: 18rem;">
  <img src="https://i.postimg.cc/SRmcJgCL/project2.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Second project, but first e-com project.</h5>
    <p class="card-text"></p>
  </div>
  <div class="card-body">
    <a href="https://boujeebirds.netlify.app" class="card-link"><button class="see">View</button></a>
  </div>
</div> 
<h3>
  Project Name: Boujee Birds
</h3>
</div>


<div class="contain">
<div class="card" style="width: 18rem;">
  <img src="https://i.postimg.cc/0y4Gcd1x/project3.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">My First Ever JavaScript Project</h5>
    <p class="card-text"></p>
  </div>
  <div class="card-body">
    <a href="https://jake-calculator.netlify.app" class="card-link"><button class="see">View</button></a>
  </div>
</div>
<h3>
  Project Name: Calculator
</h3>
</div>



</template>

<script>



</script>

<style>

h1{
    margin-top: 30px;
    margin-bottom: 30px;
    font-size: 50px;
    text-shadow: 0 0 10px blue, 0 0 20px silver;
  }




.pro1{
    width: 350px;
    margin-bottom: 30px;
    margin-right: 30px;
    border-radius: 10px;
}

 .pro2{
    width: 350px;
    margin-bottom: 30px;
}

.pro3{
    width: 350px;
    margin-bottom: 30px;
} 

.card{
    margin-left: 15rem;
    margin-top: 30px;
    padding-top: 0;
    margin-bottom: 25px;
}

.see{
    box-shadow: 4px 3px red;
    color: blue;
    background-color: black;
}

.pro{
    animation: project 3s;
}

.contain{
  position: relative;
  border: 3px solid black;
}





</style>