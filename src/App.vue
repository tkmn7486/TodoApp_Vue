<template>
  <Title sub="Vue練習用のTodoアプリです"/>
  <Contents/>
  <!--コメントアウトに使うのはこのタグ-->
</template>

<script>
import Title from './components/Title'
import Contents from './components/Contents'

export default {
  name: 'App',
  components: {
    Title,
    Contents,
  }
}
</script>

<style>
HTML {
  height:100%;
  background-color:rgba(0, 0, 0, 0.973);
  color:rgba(176, 238, 253, 0.884);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 60px;
}
</style>