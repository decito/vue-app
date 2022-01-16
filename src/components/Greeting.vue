<template>
  <h1>{{ msg }}</h1>
</template>

<script>
  export default {
    name: 'Greeting',
    data() {
      return {
        msg: 'Hello World',
      }
    }
  }
</script>

<style scoped lang="scss">
$color: red;

h1 {
  color: $color;
}
</style>