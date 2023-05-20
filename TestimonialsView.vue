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
    
    <input name="men"  type="radio" id="Features" class="tap">
    <router-Link to="/features">
    <label for="Features">Features</label>
  </router-Link>
  
   
  
  <input name="men" type="radio" id="Partner" class="tap">
      <router-Link to="/Partner">
      <label for="Partner">Partner</label>
    </router-Link>
    
    <input name="men" type="radio" id="Testimonials" class="tap"  checked>
      
      <label for="Testimonials">Testimonials</label>

  </div>
  
  
  
  
  <div class="conteaner">
  
  
  <p dir="rtl" lang="ar" style="color:#000;font-size:17px; position: absolute; left:52em; top:0.7em; cursor: pointer; width: 200px;">اللغة العربية</p>
  </div>
  
  
  <button id="log-btn" >log in</button>

  <div class="tx1">
     WHAT OUR CLINT SAY!
    </div>

    <img class="line10" src="@/assets/line10.svg">


    <Carousel :breakpoints="breakpoints">
      
      <Slide v-for="slide in 10" :key="slide">
        <div class="carousel__item"  >
       <img class="kk" src="@/assets/sq1.svg">
       <img class="cot" src="@/assets/cot.svg">
       <p class="ttt2">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.
        FUSCE.LOREM IPSUM DOLOR SIT AMET
        CONSECTETUR. FUSCE.
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.
        FUSCE.LOREM IPSUM DOLOR SIT AMET
        CONSECTETUR. FUSCE.
      </p> 
       <img class="ali" src="@/assets/aali.svg">
       <p class="ttt3">
        Ali Ahmed
       </p>
       <p class="ttt4">
        Fashion Company
       </p>

      </div>
      </Slide>
  
      <template #addons>
        <Navigation />
      </template>
    </Carousel>


  <div class="boox">
     <div class="ttt5">
      Always Listening, Always Understanding
     </div>
     <input type="text" class="text">


     <button id="send" >Send</button>
    </div>


    <div class="orange"></div>

<img class="logot" src="@/assets/logot.svg">

<div class="t9">
  An Electronic Platform Established In 2017 That  </div>

  <div class="t10">
Seeks To Be The First Platforms In Logistics Services</div>

<div class="t11">
And The Leader In Delivery And Freight Services </div>


<img class="mar" src="@/assets/mar.svg">

<div class="t12">
Lines Company For</div>

<div class="t13">
Programming And Marketing </div>

<div class="t14">
Tax Number 34564424525252 </div>

<div class="t15">
Quick Links </div>

<img class="sh1" src="@/assets/sh1.svg">
<img class="sh2" src="@/assets/sh2.svg">
<img class="sh3" src="@/assets/sh3.svg">
<img class="sh4" src="@/assets/sh4.svg">
<img class="sh5" src="@/assets/sh5.svg">

<div class="t16">
Terms And Conditions </div>
<div class="t17">
Privacy Of Use </div>
<div class="t18">
Return Policy </div>
<div class="t19">
Business Cooperation </div>
<div class="t20">
Developers Portal </div>


<div class="t21">
Get In Touch</div>

<img class="tele" src="@/assets/tele.svg">


<div class="t22">
+972595111957 </div>

<div class="t23">
+972595111957 </div>

<div class="t24">
Saudi Arabia, Dammam </div>

<img class="sms" src="@/assets/sms.svg">
<img class="loc" src="@/assets/loc.svg">

<img class="saudi" src="@/assets/saudi.svg">
<img class="stc" src="@/assets/stc.svg">
<img class="visa" src="@/assets/visa.svg">

<img class="e" src="@/assets/e.svg">
<img class="e1" src="@/assets/e1.svg">
<img class="e2" src="@/assets/e2.svg">

<img class="e3" src="@/assets/e3.svg">
<img class="e4" src="@/assets/e4.svg">
<img class="e5" src="@/assets/e5.svg">
  </template>

<script lang="ts">
  
import { defineComponent } from 'vue'
import { Carousel, Navigation, Slide } from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

export default defineComponent({
name: 'BreakPoints',
components: {
  Carousel,
  Slide,
  Navigation,
},
data: () => ({
  // carousel settings

  // breakpoints are mobile first
  // any settings not specified will fallback to the carousel settings
  breakpoints: {
    // 700px and up
    700: {
      itemsToShow: 3,
      snapAlign: 'left',
    },
    // 1024 and up
  1024: {
      itemsToShow: 3,
      snapAlign: 'start',
    },
  },
}),
})
</script>

<style>
.tx1{
      color:black;
      position: absolute;
      font-weight: bolder;
      top:9em;
      left:4em;
      font-size: larger;

    }
    
    .line10{
      position: absolute;
      top:9em;
      left:5em;
      width: 55px;
    }
.boox{
position: absolute;
width: 350px;
height: 360px;
left: 53.5em;
top: 15em;
border-radius: 9.69444px;
background:#0E2944;
}

.text{
  color: #1b1a1a;
  position: absolute;
  width: 280px;
  height: 170px;
  border-radius: 9.69444px;
  border: none;
left:0.8em;
  top:2em;
  background:#ffffff;

}

#send {
  
  position: absolute;
  width: 280px;
  height: 40px;
  left: 2.5em;
  background-color:  #ED4445;
  border-radius: 7px;
  font-family: 'Poppins';

  font-weight: 500;
  font-size: 16px;
 border-color: #F5AC01;
 border: none;
  color: #FFFFFF;
  top:19em;
}

.ttt5{
  font-size:20px;
  width: 300px;
  left:1em;
  text-align: left;
  top:1em;
  position:absolute;
  color: #ffffff;
}


.carousel__item {
  min-height: 200px;
  width: 85%;

  font-size: 20px;
  border-radius: 8px;

  align-items: left;
 margin-top:11.5em;
}

.carousel__slide {
 
  align-items: left;
  left:-2em;

  margin: 10px;
}

.carousel__prev{
 left:23em;
  border-radius: 25px;
  height: 20px;
  color:#ce3535;
  box-sizing: content-box;
  position: absolute;
  top:7em;
  border: 2px solid red;
  width: 20px;
}
.carousel__next {
  box-sizing: content-box;
top:-12em;
border: 2px solid red;
  width: 20px;
position: absolute;
margin:570px;
right: -5em;
border-radius: 25px;
  height: 20px;
  color:#ce3535;
}

.kk{
  height: 300px;
  width: 360px;
  padding: -1em;
  left:1em;
}
.ali{
  position: absolute;
  top:13.5em;
  left:3em;
  height: 50px;
}

.ttt3{
  position: absolute;
  top:13em;
  left:7em;
  color: #000;

}

.ttt4{
  position: absolute;
  left:11em;
  top:22.8em;
  font-size: 13px;

}

.ttt2{
  position: absolute;
  left:2em;
  top:22em;
  width: 340px;
  font-size: 15px;

}

.cot{
  position: absolute;
  top:12.5em;
  left:16em;
}


.orange{
  top: 40em;
  position: absolute;
  left: 0em;
  width: 100%;
  height: 295px;
  background-color:#0E2944;
}


.logot{
  top: 41.5em;
  position: absolute;
  left: 6em;
  width: 120px;
}


.t9{
  top: 45em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.t10{
  top: 46.8em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.t11{
  top: 48em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.mar{
  top: 50.7em;
  position: absolute;
  left: 6em;
  width: 90px;
}

.t12{
  top: 59.7em;
  position: absolute;
  left: 14.7em;
  color: #FAFAFA;
  font-size: 13.5px;
}

.t13{
  top: 62em;
  font-size: 13.5px;
  position: absolute;
  left: 14.6em;
  color: #FAFAFA;
}

.t14{
  top: 66em;
  font-size: 13.5px;
  position: absolute;
  left: 7em;
  color: #FAFAFA;
}

.t15{
  top: 33.7em;
  font-size: 20px;
  position: absolute;
  left: 30em;
  color: #FAFAFA;
}

.sh1{
  top: 46.3em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}

.sh2{
  top: 48.6em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}

.sh3{
  top: 51em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}

.sh4{
  top: 53.7em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}

.sh5{
  top: 56.2em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}



.t16{
  top: 52.6em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.t17{
  top: 55.4em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.t18{
  top: 58em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.t19{
  top: 61.2em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.t20{
  top: 64em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.tele{
  top: 51em;
  font-size: 14px;
  position: absolute;
  left: 67em;
}

.t21{
  top: 33.6em;
  font-size: 20px;
  position: absolute;
  left: 47em;
  color: #FAFAFA;
}

.t22{
  top: 51.4em;
  font-size: 14px;
  position: absolute;
  left: 70em;
  color: #FAFAFA;
}

.t23{
  top: 54em;
  font-size: 14px;
  position: absolute;
  left: 70em;
  color: #FAFAFA;
}
.t24{
  top: 56.6em;
  font-size: 14px;
  position: absolute;
  left: 70em;
  color: #FAFAFA;
}

.sms{
  top: 54em;
  font-size: 14px;
  position: absolute;
  left: 67em;
}

.loc{
  top: 56.4em;
  font-size: 14px;
  position: absolute;
  left: 67em;
}

.saudi{
  top: 59.5em;
  font-size: 14px;
  position: absolute;
  left: 67em;

}

.stc{
  top: 59.5em;
  font-size: 14px;
  position: absolute;
  left: 74em;
}

.visa{
  top: 59.5em;
  font-size: 14px;
  position: absolute;
  left: 78em;
}


.e{
  top: 63.2em;
  font-size: 14px;
  position: absolute;
  left: 77em;
}

.e1{
  top: 63.2em;
  font-size: 14px;
  position: absolute;
  left: 72em;
}
.e2{
  top: 63.2em;
  font-size: 14px;
  position: absolute;
  left: 67em;
}




.e3{
  top: 64em;
  font-size: 14px;
  position: absolute;
  left: 77.7em;
}

.e4{
  top: 64em;
  font-size: 14px;
  position: absolute;
  left: 72.7em;
}
.e5{
  top: 64em;
  font-size: 14px;
  position: absolute;
  left:67.8em;
}

</style>