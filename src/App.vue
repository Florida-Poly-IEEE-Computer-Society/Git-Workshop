<script setup>
    import { ref } from 'https://unpkg.com/vue@3/dist/vue.esm-browser.js'
    const message = ref("Hello GitHub Workshop!")
</script>

<template>
  <h1>{{ message }}</h1>
</template>
