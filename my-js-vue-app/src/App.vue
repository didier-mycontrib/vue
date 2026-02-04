<script setup>
   import Calculatrice from "./Calculatrice.vue";
   let msg="hello world";
</script>

<template>
  <h1>My Vue App</h1>
  <p class="c1"> {{ msg }}</p>
  <hr/>
  <calculatrice></calculatrice>
</template>

<style scoped>
   .c1{
    color:red;
   }
</style>
