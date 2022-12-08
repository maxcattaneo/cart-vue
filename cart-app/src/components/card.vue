<template>
    <div id="card" class="w-[300px] h-[420px] m-10 flex flex-col justify-between bg-white p-2 rounded ">
        <img :src="beer.image_url" class="h-[250px] w-[100px] mx-auto" alt="">
        <a class="text-xl" href="#">{{beer.name}}</a>
        <div class="flex justify-between">
            <span>{{beer.ibu}}€</span>
            <span>10 X 226,00</span>
        </div>
        <Button class="bg-green-500" :text="'Add to cart'"/>
     </div>
</template>

<script setup>
import Button from "./button.vue";
const props = defineProps(['beer']);
</script>

<style>

</style>