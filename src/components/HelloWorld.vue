<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1 id="h1-hello">{{ msg }}</h1>
</template>

<style scoped>
#h1-hello {
  color: #0046dd;
  text-shadow: 2px 3px black;
}

</style>
