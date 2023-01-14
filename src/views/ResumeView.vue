<template>
    
    <h1 class="head-res">Resume</h1>

<h4>
    My first casual job since finishing high school.
   <h4> I was in a sales assistant position for 3 months.</h4>
    Permanent for 2 months thereafter.
</h4>
<img class="bnt" src="../assets/bladesandtriggers.jpg">

<h4>
    This was my second job after working as a sales person.
<h4>Duration was three months. My position was warehouse assistant.</h4>
    On of my duties were helping the machine operators to maintain the 
    machines.
</h4>
<img class="vtl" src="../assets/vital.jpg">

<h4>Currently I am a software development student at </h4>
<h4>Life Choices Academy. Starting date was September to present. </h4>
<img class="LCA" src="../assets/LIFE-CHOICES-ICON-ON-GREEN.png">





</template>

<script>

export default{
  name: 'ResumeView',
    data(){
      return{
        ResumeView:[
            {
                name:'Blades & Triggers',
                period: '2 months',
                description: 'My first casual job since finishing high school.',
                image: 'bladesandtriggers.jpg'

                
            }
        ]
      }
    }
}


</script>


<style>

h1{
    padding-top: 20px;
}

.bnt{
    width:300px;
}

.vtl{
    width: 300px;
}

.LCA{
    width: 300px;
}

img{
    padding-top:30px;
    padding-bottom: 30px;
}
.lang-logos{
    width: 300px;
}

</style>