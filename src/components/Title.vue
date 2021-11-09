<template>
  <div class="title">
    <h1>{{ title }}</h1>
    <p>!!!{{ sub }}!!!</p>
  </div>
</template>

<script>
export default {
  name: 'Title',
  props: {
    title : String,
    sub : String,
  }
}
</script>

<style>
</style>