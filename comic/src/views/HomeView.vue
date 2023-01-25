<template>
  <div class="home">   
   <div class="container">

   <div class="row">
   <div class="col-md-4 colg p1 ">1</div>
   <div class="col-md-6 colg p2 ">2</div>
   </div>


   <div class="row">
   <div class="col colg p3">3</div>
   <div class="col colg p4">4</div>
   <div class="col colg p5">5</div>
   </div>

      
   <div class="row">
   <div class="bg-success col-md-2 colm">6</div>
   <div class="col-md-4 colm">7</div>
   <div class="col-md-5 colm">8</div>
   </div>
   
   <br />
   <br />
   <br />

   <div class="row">
   <div class="col-md-4 colg">9</div>
   <div class="col-md-6 colg">10</div>
   </div>


   <div class="row">
   <div class="col colg">11</div>
   <div class="col colg">12</div>
   <div class="bg-success col colg">13</div>
   </div>

      
   <div class="row">
   <div class="col-md-2 colm">14</div>
   <div class="col-md-4 colm">15</div>
   <div class="col-md-5 colm">16</div>
   </div>
   
   
   
   
   
   
   </div>

   <hr />


   <br />
   <br />
   <br />

  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {

  }
}
</script>

<style scoped type="scss">
.p1{
  background-image: url("../assets/pics/1.png");
  background-position: center;
  background-size: cover;

  background-repeat: no-repeat;
}
.p2{
  background-image: url("../assets/pics/2.png");
  background-position: center;
  background-size: cover;

  background-repeat: no-repeat;
}



.p3{
  background-image: url("../assets/pics/3.png");
  background-position: center;
  background-size: cover;

  background-repeat: no-repeat;
}

.p4{
  background-image: url("../assets/pics/4.png");
  background-position: center;
  background-size: cover;

  background-repeat: no-repeat;
}

.p5{
  background-image: url("../assets/pics/5.png");
  background-position: center;
  background-size: cover;

  background-repeat: no-repeat;
}
</style>
