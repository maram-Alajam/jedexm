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
    <input name="men" type="radio" id="About" class="tap">
    <router-Link to="/about">
    <label for="about">About Us</label>
    </router-Link>
    
    <input name="men"  type="radio" id="Features" class="tap"  checked>
  
    <label for="Features">Features</label>

  
  
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

  <img class="offi" src="@/assets/office.svg">
  <img class="feat" src="@/assets/feat.svg">
  <img class="line" src="@/assets/line9.svg">

  <div class=" txx">
Features
</div>

<div class="tx1">
  WHAT MAKE AS SPECIAL
</div>

<div class="tx2">
Inside And Out Side The Region
</div>
<div class="tx3">
  Full Coverage
</div>
<div class="tx4">
  All Kinds OF Product
</div>
<div class="tx5">
  Online Pament
</div>
<div class="tx6">
  Delivery IN Less Than An Hour
</div>
<div class="tx7">
  Door Pickup
</div>

<img class="loca" src="@/assets/location.svg">
<img class="w" src="@/assets/world.svg">
<img class="p" src="@/assets/product.svg">
<img class="o" src="@/assets/online.svg">
<img class="dev" src="@/assets/dev.svg">
<img class="door" src="@/assets/door.svg">
<img class="carat" src="@/assets/carat.svg">
<img class="dbab" src="@/assets/dbab.svg">
<div class="R">
PRICES START FROM 15 PER 150 KILOGRAMS OUTSIDE AND INSIDE THE CITY
</div>

<button id="order" >Order A Caption Now</button>
  </template>



<style>

.offi{
    height: 400px;
    left:7em;
    
    top:9em;
    position: absolute;
}

.feat{
    position: absolute;
    height: 400px;
    top:9em;
    left:30em;
}

.line{
    position: absolute;
    top:11em;
    left:32em;
}

.txx{
    color: #c0bebe;
    position: absolute;
    top:13em;
    left:36.5em;
    font-size: 14px;
    font-family: 'Poppins';
    font-weight: lighter;
  }

  .tx1{
    position: absolute;
    top:11em;
    left:27em;
    font-size:19px;
    font-weight:bold;

  }

  .loca{
    position: absolute;
    top:15em;
    left:32em;
  }

  .tx2{
    position: absolute;
    top:15.5em;
    left:35em;
  }

  .w{
    position: absolute;
    top:18em;
    left:32em;
  }

  .tx3{
    position: absolute;
    top:18.5em;
    left:35em;
  }

  .tx4{
    position: absolute;
    top:21.5em;
    left:35em;
  }
  .p{
    position: absolute;
    top:21em;
    left:32em;
  }
.tx5{
  position: absolute;
    top:24.5em;
    left:35em;
}
  .o{
    position: absolute;
    top:24em;
    left:32em;
  }
.tx6{
  position: absolute;
    top:27.5em;
    left:35em;
}
  .dev{
    position: absolute;
    top:27em;
    left:32em;
  }
.tx7{
  position: absolute;
    top:30.5em;
    left:35em;
}
  .door{
    position: absolute;
    top:30em;
    left:32em;
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
</style>