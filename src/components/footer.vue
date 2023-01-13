<template>
<footer class="foot">
    <div class="container">
    <footer class="d-flex flex-wrap justify-content-between align items-center py-3 my-4 border-top">
        <p class="col-md-4 mb-0 ">Jake Jansen © 2023</p>
        <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
            <li class="ms-3"><a class="insta" href="https://www.instagram.com/africa_777/"><button class="foot-btn1"><i class="fa-brands fa-instagram"></i
                ></button></a></li>
            <li class="ms-3"><a class="facebook" href="https://www.facebook.com/jake.jansen.372/"> <button class="foot-btn2"><i class="fa-brands fa-facebook"></i></button>
                </a></li>
            <li class="ms-3"><a class="tiktok"  href="https://www.tiktok.com/foryou?lang=en"><button class="foot-btn3"><i class="fa-brands fa-tiktok"></i></button></a></li>
        </ul>
    </footer>
</div>

</footer>
</template>

<script>

export default{
    name: 'Footer',
}

</script>

<style>

footer{
    background-color: white;
    /* background-image: linear-gradient(to bottom,rgb(153, 0, 17), pink, blue );
     */
     /* background-color: rgb(206, 191, 191); */

     background: transparent;
}


p{
    color: black;
}


button{
    border-radius: 20px;
}


.foot-btn1{
    background-image: radial-gradient( rgb(138, 58, 185), rgb(233, 89, 80), rgb(188, 42, 141), rgb(252, 204, 99), rgb(251, 173, 80), rgb(205, 72, 107));
}

.foot-btn2{
    background-color: rgb(66, 103, 178);
}

.foot-btn3{
    background-image: radial-gradient(rgb(255, 0, 80), rgb(0, 242,234), rgb(0, 0, 0))
}

button:hover {
  animation: btnAnimate 0.5s forwards;
}

@keyframes btnAnimate {
  from {transform: scale(1)}
  to {transform: scale(1.2)}
}





</style>
