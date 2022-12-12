<template>
  <article>
    <button @click="(signedIn = !s)" v-if="!signedIn">Log In</button>
    <button @click="(signedIn = !s)" v-if="signedIn">Log Out</button>
  </article>
</template>

<script setup>
import { ref } from 'vue'
const signedIn = ref(false)
</script>

<style>

</style>
