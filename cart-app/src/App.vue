<template>
    <body>
        <header class="h-20 bg-gray-700 flex justify-center items-center">
            <div class="bg-gray-700 flex justify-center text-white h-10 w-full ">
                <nav class="flex items-center justify-evenly w-1/2">
                    <a href="#">AllProducts</a>
                    <a href="#">Smartphones</a>
                    <a href="#">Notebooks</a>
                </nav>
                <button class="bg-sky-500 hover:bg-blue-700 font-bold py-2 px-6 rounded flex">Cart<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6 ml-2">
  <path d="M2.25 2.25a.75.75 0 000 1.5h1.386c.17 0 .318.114.362.278l2.558 9.592a3.752 3.752 0 00-2.806 3.63c0 .414.336.75.75.75h15.75a.75.75 0 000-1.5H5.378A2.25 2.25 0 017.5 15h11.218a.75.75 0 00.674-.421 60.358 60.358 0 002.96-7.228.75.75 0 00-.525-.965A60.864 60.864 0 005.68 4.509l-.232-.867A1.875 1.875 0 003.636 2.25H2.25zM3.75 20.25a1.5 1.5 0 113 0 1.5 1.5 0 01-3 0zM16.5 20.25a1.5 1.5 0 113 0 1.5 1.5 0 01-3 0z" />
</svg>
</button>
            </div>
        </header>
        <div>
            <div class="card flex flex-col justify-between bg-white p-2 rounded">
                <img class="image-card" src="https://img.freepik.com/foto-gratis/florero-clip-papel-ordenador-portatil-cuadernos-anteojos-contra-pared-pintada-blanco_23-2147979119.jpg?w=2000" alt="">
                <a class="text-xl" href="#">Acá va el articulo</a>
                <div class="flex justify-between">
                    <span>R$ 2259,59</span>
                    <span>10 X 226,00</span>
                </div>
                <button class="bg-sky-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded flex justify-center">Add to cart <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6 ml-2">
  <path d="M2.25 2.25a.75.75 0 000 1.5h1.386c.17 0 .318.114.362.278l2.558 9.592a3.752 3.752 0 00-2.806 3.63c0 .414.336.75.75.75h15.75a.75.75 0 000-1.5H5.378A2.25 2.25 0 017.5 15h11.218a.75.75 0 00.674-.421 60.358 60.358 0 002.96-7.228.75.75 0 00-.525-.965A60.864 60.864 0 005.68 4.509l-.232-.867A1.875 1.875 0 003.636 2.25H2.25zM3.75 20.25a1.5 1.5 0 113 0 1.5 1.5 0 01-3 0zM16.5 20.25a1.5 1.5 0 113 0 1.5 1.5 0 01-3 0z" />
</svg>
</button>

            </div>
        </div>
    </body>

  
</template>

<script setup>
import {ref} from "vue";
</script>

<style>
.card{
    width: 300px;
    height: 420px;
    margin:16px
}
.image-card{
    height: 250px;
}

</style>
