<template>
    <v-app-bar app color="#33569D" flat class="" >
      <v-img src="../assets/logo.png"></v-img>
      <!-- <h2 >GS HYDRO TECH</h2> -->
      <v-spacer></v-spacer>
      <v-btn text @click="scroll('home')" class="text-yellow">Home</v-btn>
      <v-btn text @click="scroll('about')"  class="text-white" >About</v-btn>
      <!-- <v-btn text @click="scroll('portfolio')"  >Portfolio</v-btn> -->
      <v-btn text @click="scroll('products')" class="text-white"> Products</v-btn>
      <!-- <v-btn text @click="scroll('page')"  > Page</v-btn> -->
      <!-- <v-btn text @click="scroll('biog')"  > Biog</v-btn> -->
      <v-btn text @click="scroll('contact')"  class="text-white"> Contact</v-btn>
    </v-app-bar>
  </template>
  
  <script>
  export default {
    methods: {
      scroll(refName) {
        const element = document.getElementById(refName);
        element.scrollIntoView({ behavior: "smooth" });
      },
    },
  };
  </script>
  
  <style>
  </style>