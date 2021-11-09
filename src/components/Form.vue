<template>
  <div class="form">
    <p>{{ic}}</p>
    <input><button>ボタン</button>
  </div>
</template>

<script>
export default {
  name: 'Form',
  props: {
    ic:String
  }
}
</script>

<style>
</style>