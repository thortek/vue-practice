<template>
    <h1>{{ msg }}</h1>
</template>

<script>
export default {
  name: 'IamGroot',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h1 {
    color: darkgreen;
    background-color: bisque;
    text-align: center;
}
</style>