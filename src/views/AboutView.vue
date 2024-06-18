<template>
  <div class="about">
    <input v-model="name" />
    <br />
    <h1>This is a page about {{ guy }}, {{ name }}</h1>
  </div>
</template>

<script setup>
import { ref } from 'vue'

// const props = defineProps(['guy'])

const name = ref('fttf')
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
