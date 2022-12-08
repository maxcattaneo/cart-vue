<template>
        <header class="h-20 bg-gray-700 flex justify-center items-center">
            <div class="bg-gray-700 flex justify-center text-white h-10 w-full ">
                <nav class="flex items-center justify-evenly w-1/2">
                    <a href="#">AllProducts</a>
                    <a href="#">Smartphones</a>
                    <a href="#">Notebooks</a>
                </nav>
                <Button :text="'Cart'"/>
            </div>
        </header>
  
</template>

<script setup>
import Button from "./button.vue"

</script>

<style>

</style>