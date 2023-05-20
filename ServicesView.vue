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
  
    <input name="men" type="radio" id="Services" class="tap"  checked>
   
    <label for="Services">Services</label>
 
  
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
  </template>