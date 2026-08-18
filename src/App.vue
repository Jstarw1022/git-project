<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <main>
    <h1>Vue 3 + Vite</h1>
    <p>环境搭建成功！</p>
    <button @click="count++">点击计数：{{ count }}</button>
  </main>
</template>
