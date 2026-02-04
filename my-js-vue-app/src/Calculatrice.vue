<script setup>
   import { ref } from 'vue';
   let a=0;
   let b=0;
   let res=ref(0);

   function add(){
      res.value= a+b;
      console.log(`add() with a=${a} b=${b} res=${res}`)
   }
</script>

<template>
  <h1>Calculatrice</h1>
  <p> a: <input type="number" v-model="a" /></p>
  <p> b: <input type="number" v-model="b" /></p>
  <p><button  @click="add">addition</button></p>
  <p> res: {{ res }}</p>
</template>

<style scoped>

</style>
