<script>
export default {
  data() {
    return {
      h1_message: 'Hello_World!',
    }
  }
}
</script>

<template>
  <header>

    <h1>{{ h1_message }}</h1>

  </header>
</template>

<style>
header {
  min-height: 100px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

h1 {
  color: blue;
  font-style: italic;
  text-align: center;
  text-shadow: 2px 1px rgb(131, 131, 131);
}
</style>
