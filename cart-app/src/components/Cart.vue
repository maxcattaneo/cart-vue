<template>
    <div class="arrow-up absolute right-96 z-10"></div>
    <div class="bg-white w-96 rounded-md absolute right-[250px] mt-2 p-2 z-10"> 
        <div>
            <p>No products :/</p>
        </div>
        <div class="flex justify-between">
            <img class="w-20 h-20" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStMITIzNGQvzG0QbGumV4YP54Ch0EyJtbc2Q&usqp=CAU" alt="">
            <div class="flex-col ">
                <p class="text-lg my-2">Nombre de la cerveza</p>
                <p>Precio</p>
            </div>
            <img src="#" alt="">
        </div>
        <div class="flex justify-between items-center">
            <p>Total: €</p>
            <Button :text="'View cart'"/>
        </div>
        
    </div>
</template>

<script setup>
import Button from "./button.vue";

</script>

<style lang="scss" scoped>

</style>