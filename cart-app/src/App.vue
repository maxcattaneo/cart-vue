<template>
     <Header/>
     <Cart/>
     <section class="grid grid-cols-3 justify-center mx-20 gap-6 mt-6 place-items-center">
      <div v-for="(beer, index) in beers" :key="index" >
        <Card :beer="beer" />
      </div>
     </section>
</template>

<script setup>
import Header from "./components/header.vue";
import Card from "./components/card.vue";
import Cart from "./components/Cart.vue"
import {ref} from "vue";
const beers = ref([]);
async function getBeer() {
  const res = await fetch("https://api.punkapi.com/v2/beers");
  const finalRes = await res.json();
  beers.value = finalRes;
  console.log(finalRes);
}
getBeer();
</script>

<style>

</style>
