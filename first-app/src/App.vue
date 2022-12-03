<template>
  <h2>Hola {{name}}!</h2>
  <input type="mail" v-model="email"/>
  <p :="email">{{email}}</p>
  <button @click="showEmail">Show email</button>
</template>

<script setup>
import {ref} from "vue";
const name = ref ("Max");
const email = ref ("maxi@gmail.com");
function showEmail(){
  
}

</script>

<style scoped>
h2{
  color:red;
}
.show{
  display: block;
}
.hidden{
  display: none;
}

</style>
