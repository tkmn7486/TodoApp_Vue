<template>
  <Title title="Test-App" sub="このページはテストで作成したものです。"/>
  <Form ic="以下に文字を入力"/>
  <Contents con="ボタンを押すと以下の文字が変わります。">
</template>

<script>
import Title from './components/Title'
import Form from './components/Form'
import Contents from './components/Contents'

export default {
  name: 'App',
  components: {
    Title,
    Form,
    Contents,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>