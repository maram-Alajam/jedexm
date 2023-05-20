<template>
  
  <div class="home">
    
  <img class="pubg" src="@/assets/bub.png">
  <img class="img" src="@/assets/img.png">

  </div>
 
  <div class="red">
  <img class="number" src="@/assets/number.svg">
  <img class="loct" src="@/assets/locat.svg">
  <img class="login" src="@/assets/login.svg">
 
 <img class="line8" src="@/assets/Line8.svg">
  
</div>
<i class="bi bi-instagram"></i>
<i class="bi bi-whatsapp"></i>
<i class="bi bi-twitter"></i>

<div class="white">

</div>

  <img class="back-jedex" src="@/assets/back-jedex.svg">
  <img class="logo-jedex" src="@/assets/logo-jedex.svg">

  
  <div class="menu">
  <input name="men" type="radio" id="app" class="tap" checked>
  <label for="app">Home</label>
  
  <input name="men" type="radio" id="About" class="tap">
  <router-Link to="/about">
  <label for="about">About Us</label>
  </router-Link>
  
  <input name="men"  type="radio" id="Features" class="tap">
  <router-Link to="/features">
  <label for="Features">Features</label>
</router-Link>

 

<input name="men" type="radio" id="Partner" class="tap">
    <router-Link to="/Partner">
    <label for="Partner">Partner</label>
  </router-Link>
  
  <input name="men" type="radio" id="Testimonials" class="tap">
    <router-Link to="/Testimonials">
    <label for="Testimonials">Testimonials</label>
  </router-Link>
</div>




<div class="conteaner">


<p dir="rtl" lang="ar" style="color:#000;font-size:17px; position: absolute; left:52em; top:0.7em; cursor: pointer; width: 200px;">اللغة العربية</p>
</div>


<button id="log-btn" >log in</button>
<div class="text">
<h3> safe & Faster</h3>

  <div class="tex">
    <h6> Logistic Services</h6>
  </div>
</div>



<input class="box-text" placeholder=" Enter Your Order ID  ">


<button id="track-btn" >Track</button>
</template>

<script lang="ts">

</script>


<style>
.pubg{
  position: absolute;
  width: 100%;
  left:0em;
  top:0em;
  height: 100%;
  overflow-y: hidden;
  overflow-x: hidden;
  overflow: hidden;
}
.img{
  position: absolute;
  width: 100%;
  left:0em;
  top:0em;
  height: 100%;
}
.back-jedex{
position: absolute;
top:0em;
left:0em;
width: 500px;
}

.logo-jedex{
  top:1em;
  left:9em;
  position: absolute;
}

.red{
  background: #ED4445;
  position: absolute;
  width: 100%;
  left:0em;
  top:0em;
  height: 60px;
}


.white{
  background: #fdfdfd;
  position: absolute;
  width: 100%;
  left:0em;
  top:3.4em;
  height: 60px;
}

.number{
  top:1.5em;
  position: absolute;
 left:32em;
 width: 110px;
}

.loct{
position: absolute;
top:1.5em;
left:41em;
width: 150px;
}

.login{
  position: absolute;
  left:58em;
  top:1.2em;
  
  width: 70px;
}


.bi-instagram{
  position: absolute;
  top:1.4em;
  left:66em;
  color: #FFFFFF;

}



.line8
{
  position: absolute;
  top:1em;
  left:63em;
  color:#f9f1f1;
  

}

.bi-whatsapp{
  position: absolute;
  top:1.4em;
  left:64em;
  color: #FFFFFF;
}

.bi-twitter{
  position: absolute;
  top:1.4em;
  left:68em;
 
  color: #FFFFFF; 
}


.menu{
  position:absolute;
  left:19em;
  padding: 8px;
  cursor: pointer;
}

label{
 position: relative;
 color: #353535;
 font-family: 'Poppins';
 font-weight: bold;
 font-size: 16px;
 padding-bottom:  17px;
 padding-left: 3px;
 padding-top: 18px;
 padding-right: 10px;
 cursor: pointer;
 left:7em;
 margin-left: 15px;

}

a:link{
    text-decoration: none;
  }

input:checked +label{

  color: #ED4445;
  
  
}

label:checked{
  size:20px;
}
.tap{
  display: none;
 tab-size: 20px;
}

.conteaner{
  position: absolute;
 
  top:3em;
  left:5em;
}
#log-btn {

position: absolute;
width: 80px;
height: 40px;
left: 70em;
background-color:#0E2944;
border-radius: 7px;
font-family: 'Poppins';

font-weight: 500;
font-size: 16px;
border-color: #F5AC01;
border: none;
color: #FFFFFF;
top:4em;
}

.text{
position: absolute;
color: #FAFAFA;
top:3.4em;
font-size: 45px;
text-align: left;
width: 500px;
left:10em;

font-family:'Poppins';
}

.tex{
position: absolute;
color: #FAFAFA;
font-size: 35px;
left:2em;
top:2em; 
width: 350px;

}



/*box*/
.box-text{
  background: #FAFAFA;
color: #000;
position: absolute;
width: 350px;
height: 50px;
border-radius: 9.69444px;
border: none;
left:32em;
top:27.5em;

}

#track-btn {

position: absolute;
width: 90px;
height: 53.4px;
left: 47em;
background-color:#ED4445;
border-radius: 7px;
font-family: 'Poppins';
padding-top: 10px;
padding-bottom: 10px;
font-weight: 500;
font-size: 16px;
border-color: #F5AC01;
border: none;
color: #FFFFFF;
top:22.9em;
}
</style>