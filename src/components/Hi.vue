<template>
  <div class="container">
    <h1>Hi {{ name }}</h1>
    <p></p>
  </div>
</template>

<script>
export default {
  name: "HiComponent",
  props: {
    name: String
  }
}
</script>

<style scoped>

</style>
