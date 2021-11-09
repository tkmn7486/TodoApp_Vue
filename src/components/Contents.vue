<template>
  <div class="contents">
    <p>コンテンツをここに表示</p>
    <p>{{con}}</p>
  </div>
</template>

<script>
export default {
  name:'Contents',
  props: {
    con:String
  }
}
</script>

<style>
</style>