<script setup>

  //Declare teh variable 
  // const country = "Bangladesh"

  // function greet () {
  //   alert("Hello World")
  // }

  import { ref } from 'vue';

  // const count = ref(0);

  // const increment = () => {
  //   count.value ++;
  // }

  // function increment5 () {
  //   count.value += 5;
  // }

  const time = "Morning";


  //WE HAVE DECLARE A ARRAY -> from -> ref()
  const countries = ref ([
    {name: 'Nigeria' , capital: 'Abuja'},
    {name: 'Ghana' , capital: 'Accra'},
    {name: 'Kenya' , capital: 'Nairobi'},
    {name: 'South Africa' , capital: 'Pretoria'},
    {name: 'Egypt' , capital: 'Cairo'},
  ])


</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

    <!-- <h1>Welcome To the {{ country }} . {{ count }}</h1>
    <p>This is Simple Vue-3 app created</p>
    <p>The Number is {{ count }}</p>
    <button @click="increment()">Add Number</button>
    <button @click="increment5()">Increment 5</button> -->
    <!-- <button @click="greet()">Greet</button> -->


    <div class="wrapper">

      <!-- If Else StateMent in Vue -->
       <!-- <v-if :time="time === 'morning'">
          <h1>Good Morning</h1>
       </v-if> -->


       <!-- loop using Vue -->
       <h1>Countries With Capital</h1>
       <ul>
        <li v-for="country in countries" :key="country.name">
            {{ country.name }} - {{ country.capital }}
        </li>
        <li v-for="country , index in countries" :key="index">
            {{ index }} {{ country.name }} - {{ country.capital }}
        </li>
       </ul>

    </div>




</template>

<style scoped>
</style>
