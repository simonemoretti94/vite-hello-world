<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>

    <HelloWorld msg="Vite_hello_world!" />

  </header>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

git config --global user.email "you@example.com"
git config --global user.name "Your Name"