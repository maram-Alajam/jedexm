<template>
  
  <div class="home">
    
 

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
  <input name="men" type="radio" id="app" class="tap" >

  <router-Link to="/main">
  <label for="app">Home</label>
</router-Link>
  <input name="men" type="radio" id="About" class="tap"  checked>
  
  <label for="about">About Us</label>
  
  
  <input name="men"  type="radio" id="Features" class="tap"  >
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


<div class="line9"></div>
<div class=" txx">
  About Us
</div>

<div class="txx2">
  JEDEX PROVIDING A REIABL SERVICES
</div>

<div class="txx3">
    An Electronic Platform Established in 2017
    That Seeks To Be The First Platform in
     Logistics Services And The Leader In Delivery
     And Freight Services Through A Wide
     Network Of Companies And Individuals And
     A Fleet Of Drivers Available Around The 
     Clock Throughout The Region
  </div>
  <img class="office" src="@/assets/office.svg">
<img class="carat" src="@/assets/carat.svg">
<img class="dbab" src="@/assets/dbab.svg">
  <div class="R">
PRICES START FROM 15 PER 150 KILOGRAMS OUTSIDE AND INSIDE THE CITY
</div>

<button id="order" >Order A Caption Now</button>
</template>



<style>


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

.line9{
  background: #ED4445;
  position: absolute;
  width: 48px;
  left:6em;
  top:12em;
  height: 3px;
}

.txx{
    color: #c0bebe;
    position: absolute;
    top:10.5em;
    left:5em;
    font-size: 19px;
    font-family: 'Poppins';
    font-weight: lighter;
  }


  .txx2{
    color: #0a0a0a;
    position: absolute;
   left:3.5em; 
   font-size: 25px;
   top:10em;
   font-weight: bold;
   text-align:left;
   width:400px;
  }

  .txx3{
    position: absolute;
    top:20em;
    color: #5d5b5b;
    width: 400px;
    font-size: 16px;
    left:5.6em;
    text-align: left;
    padding-top: 2px;
    font-weight: lighter;
    line-height: 35px;
    word-spacing: 2px;
  }

  .office{
    position: absolute;
    height: 400px;
    top:10em;
  }
  .carat{
  position: absolute;
  top: 40em;
  width: 100%;
  left: 0em;
}

.dbab{
  position: absolute;
  top: 40em;
  width: 100%;
  left: 0em;
}

.R{
  position: absolute;
  top: 27em;
color: #FAFAFA;  
left: 11em;
font-weight: bold;
width:620px;
font-size: 25px;
text-align: center;
}



#order {
  box-sizing: border-box;
  position: absolute;
  width: 220px;
  height: 50px;
  left: 25em;
  background:  #ED4445;
  border-radius: 9.69444px;
  border: none;
  font-size: 18px;
  color: #FFFFFF;
top:43em;
}
</style>
