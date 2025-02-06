<script setup>
// import AlertComponent  from './components/AlertComponent.vue';
// import {data} from './data/data'

//If we export default then import it without second bracket
// import data from './data/data'


  //Import All Components
  import HeaderSection from './components/HeaderSection.vue';
  import HeroSection from './components/HeroSection.vue';
  import ProductsCollection from './components/ProductsCollection.vue';
  import CollectionsSlider from './components/CollectionsSlider.vue';
  import FeaturedProducts from './components/FeaturedProducts.vue';
  import Contact from './components/Contact.vue';
  import FooterSection from './components/FooterSection.vue';
  




</script>

<template>
  
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      
      <!-- <AlertComponent/>
      <br>
      <alert-component type="ERROR" msg="Hello world"/><br>
      <alert-component type="success" msg="Hey There"/>
      <alert-component/> -->



      <!-- Read Data from External File of js -->
      <!-- <h1>{{ data.message }}</h1>
      <h2>Today is <span>{{ data.date }}</span></h2> -->

    <!-- </div>
  </header> -->




      <!-- Header Component -->
      <header-section/>

      <!-- Hero section Component -->
       <hero-section/>
     
      <!-- Products Collection -->
      <products-collection/>

      <!-- Collections Slider  -->
      <collections-slider/>

      <!-- Featured Components -->
      <featured-products/>

      <!-- Contact us -->
      <contact image="https://images.unsplash.com/photo-1615840287214-7ff58936c4cf?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"/>

      <!-- Footer Components -->
       <footer-section/>

     

  






</template>

<style scoped>
</style>
