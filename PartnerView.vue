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
  
 
  
  <input name="men" type="radio" id="Partner" class="tap"  checked>
      
      <label for="Partner">Partner</label>
   
    
    <input name="men" type="radio" id="Testimonials" class="tap">
      <router-Link to="/Testimonials">
      <label for="Testimonials">Testimonials</label>
    </router-Link>
  </div>
  
  
  
  
  <div class="conteaner">
  
  
  <p dir="rtl" lang="ar" style="color:#000;font-size:17px; position: absolute; left:52em; top:0.7em; cursor: pointer; width: 200px;">اللغة العربية</p>
  </div>
  
  
  <button id="log-btn" >log in</button>


  <div class="tx1">
      OUR AWESOME PARTNER
    </div>

    <img class="line9" src="@/assets/line9.svg">


    <Carousel :breakpoints="breakpoints">
      
      <Slide v-for="slide in 10" :key="slide">
        <img class="carousel__item" src="@/assets/kk1.svg" >
      </Slide>
  
      <template #addons>
        <Navigation />
      </template>
    </Carousel>
  
    <img alt="ph3" class="ph3" src="@/assets/phone-back.png">
    <img class="star" src="@/assets/star.svg">
<img class="star2" src="@/assets/star2.svg">
<img class="star3" src="@/assets/star3.svg">
<img class="star4" src="@/assets/star4.svg">
<img class="star5" src="@/assets/star5.svg">
<img class="star6" src="@/assets/star6.svg">
<img class="star7" src="@/assets/star7.svg">
<div class="text">
DO YOU WANT TO INCREASE YOUR INCOME BY JOINING JEDEX ?
</div>

<div class="t1">
    Unlimited Reception Of Requests
</div>

<div class="t2">
 Requests From Stores And Individuals
</div>

<div class="t3">
Sort As Per Your Wish Accurate Delivery Confirmation
</div>

<div class="t4">
Rewarding Profits For Each Request
</div>

<div class="t5">
Arrived The Order With Your Car Or Bike
</div>

<div class="t6">
  Branch Delivery Support
</div>

<div class="t7">
100% Advance Payment
</div>
<img alt="ph" class="ph" src="@/assets/phone.svg">


<img class="google" src="@/assets/google.svg">
<img class="apple" src="@/assets/apple.svg">
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
      itemsToShow: 1,
      snapAlign: 'center',
    },
    // 1024 and up
    1024: {
      itemsToShow: 5,
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
    
    .line9{
      position: absolute;
      top:9em;
      left:5em;
      width: 55px;
    }

    .kw1{
      position: absolute;
      top:11em;
      left:5em;
      width: 165px;
      
    }

.carousel__item {
  min-height: 200px;
  width: 80%;
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
 margin-top:6em;
}

.carousel__slide {
  padding: 10px;
}

.carousel__prev{
 left:18em;
  border-radius: 25px;
  height: 20px;
  color:#ce3535;
  box-sizing: content-box;
  position: absolute;
  top:13.1em;
  border: 2px solid red;
  width: 20px;
}
.carousel__next {
  box-sizing: content-box;
top:-5.9em;
border: 2px solid red;
  width: 20px;
position: absolute;
margin:570px;
right: -1em;
border-radius: 25px;
  height: 20px;
  color:#ce3535;
}


.star{
    position: absolute;
    top: 40em;
    width: 20px;
    left: 35em;
  }

  .star2{
    position: absolute;
    top: 43em;
    width: 20px;
    left: 35em;
  }
  .star3{
    position: absolute;
    top: 46em;
    width: 20px;
    left: 35em;
  }
  .star4{
    position: absolute;
    top: 49em;
    width: 20px;
    left: 35em;
  }
  .star5{
    position: absolute;
    top: 52em;
    width: 20px;
    left: 35em;
  }
  .star6{
    position: absolute;
    top: 55em;
    width: 20px;
    left: 35em;
  }
  .star7{
    position: absolute;
    top: 58em;
    width: 20px;
   left:35em;
}

.text{
    color: #000000;
    position: absolute;
   left:25em; 
   font-size: 22px;
   top:24.5em;
   font-weight: bold;
}

.t1{
    position: absolute;
    top: 40em;
    left: 37em;
    color: rgba(104, 104, 104, 1);
  }

  .t2{
    position: absolute;
    top: 43em;
    left: 37em;
    color: rgba(104, 104, 104, 1);
  }

  .t3{
    position: absolute;
    top: 46em;
    left: 37em;
    color: rgba(104, 104, 104, 1);
  }

  .t4{
    position: absolute;
    top: 49em;
    left: 37em;
    color: rgba(104, 104, 104, 1);
  }

  .t5{
    position: absolute;
    top: 52em;
    left: 37em;
    color: rgba(104, 104, 104, 1);
  }

  .t6{
    position: absolute;
    top: 55em;
    left: 37em;
    color: rgba(104, 104, 104, 1);
  }

  .t7{
    position: absolute;
    top: 58em;
    left: 37em;
    color: rgba(104, 104,104,1);
}


.google{
    position: absolute;
    top: 62em;
    left: 35em;
    width: 180px;
    border-radius: 9.69444px;

  }

  .apple{
    position: absolute;
    top: 62em;
    left:48em;
    border-radius: 9.69444px;
    width:180px;
}


.ph{
width: 410px;
position: absolute;
left: 4em;
top: 35em;

}

.ph3{
position: absolute;
height:550px;
width: 100%;
left:0em;
top:33em;
}
</style>
