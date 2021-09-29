<template>
  <header class="hello">
    <h1>{{ msg }}</h1>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<style scoped lang="scss">
  
</style>
