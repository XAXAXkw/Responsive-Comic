<template>
    <div class="home">   
     <div class="container">
  


        <div class="row">

     <div class="col colg p01">7</div>


     </div>
<div class="row">     
<div class="col colg p02">7</div>
</div>

<div class="row">     
<div class="col colm p03">7</div>
</div>



<div class="row">
     <div class="col-md-4 colg p04 "><div class="off"><h4>off box text test</h4></div>1</div>
     <div class="col-md-6 colg p05 "><div class="off R"><h4>text test 2</h4></div></div>
     </div>


     <div class="row">     
<div class="col colm p06">7</div>
</div>
<div class="row">     
<div class="col colg p07">
    <div class="bulleF">  <h4>ボー...! Lorem rendis commodi exercitationem similique <br /> rem laboriosam quasi voluptates natus dolores?</h4></div>
</div>
</div>



     <div class="row">
     <div class="col-md-4 colg p1 "><div class="off"><h4>off box text test</h4></div>1</div>
     <div class="col-md-6 colg p2 "><div class="off R"><h4>text test 2</h4>
       <h1>ガガガ...</h1> 
     </div></div>
     </div>
  
  
     <div class="row">
     <div class="col colg p3">   <div class="bulleF">  <h1>ボー...!</h1></div>
     </div>
     <div class="col colg p4">4</div>
     <div class="col colg p5">5
        <h1 class="R">ボー...!</h1>3
     </div>
     </div>
  
        
     <div class="row">
     <div class="bg-dark col-md-2 colm">6</div>
     <div class="col-md-4 colm">7</div>
     <div class="col-md-5 colm">8</div>
     </div>
     
     <br />
     <br />
     <br />
  
     <div class="row">
     <div class="col-md-4 colg">9
     
     <h1>ボー...!</h1>
     </div>
     <div class="col-md-6 colg">10</div>
     </div>
  
  
     <div class="row">
     <div class="col colg">11</div>
     <div class="col colg">12</div>
     <div class="bg-dark col colg">13</div>
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
    name: 'TestPage',
    components: {
  
    }
  }
</script>
  
  <style scoped type="scss">
  .off{
    text-align: start;
    padding-left: 0.2rem;
background-color: rgb(255, 255, 255);
margin:0.2rem;
border:solid 3px  black;
width:fit-content;
  }
  .R{
  background-color: black;
  color:white;
  }

  .bulleF{
   display: flex;
   width:fit-content;
    background-color: beige;
    margin:5px;
    padding:0.3rem;
    border:3px black solid;
    border-radius: 3rem;
  }
  
  

  .colg{
    border:solid black 3px;
    margin:0.4rem;
    min-height:400px;
    padding: 0;
}
.colm{
    border:solid black 3px;
    margin:0.4rem;
    min-height:200px;
    padding: 0;
}

.row{
   justify-content: center;
}

.p01{
    background-image: url("../assets/pics/a01.png");
    background-position: center;
    background-size: cover;
  
    background-repeat: no-repeat;
  }
.p02{
    background-image: url("../assets/pics/a02.png");
    background-position: center;
    background-size: cover;
  
    background-repeat: no-repeat;
  }
  .p03{
    background-image: url("../assets/pics/a03.png");
    background-position: center;
    background-size: cover;
  
    background-repeat: no-repeat;
  }
  .p04{
    background-image: url("../assets/pics/a04.png");
    background-position: center;
    background-size: cover;
  
    background-repeat: no-repeat;
  }
  .p05{
    background-image: url("../assets/pics/a05.png");
    background-position: center;
    background-size: cover;
  
    background-repeat: no-repeat;
  }
  
  .p06{
    background-image: url("../assets/pics/a06.png");
    background-position: center;
    background-size: cover;
  
    background-repeat: no-repeat;
  }
  .p07{
    background-image: url("../assets/pics/a07.png");
    background-position: center;
    background-size: cover;
  
    background-repeat: no-repeat;
  }




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
  