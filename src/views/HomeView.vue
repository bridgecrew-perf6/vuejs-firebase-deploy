<template>
  <div class="home">
    <div>{{ api }}</div>
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="[PR] Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts" setup>
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
const api = process.env.VUE_APP_API_HOST;
</script>
