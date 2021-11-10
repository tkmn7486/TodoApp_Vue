<template>
  <div class="title">
    <h1 class="neon">Test-<span>To</span>do<span>A</span>pp</h1>
    <p>!!!{{ sub }}!!!</p>
  </div>
</template>

<script>
export default {
  name: 'Title',
  props: {
    title : String,
    sub : String,
  },
}
</script>

<style>
.title{
  text-align: center;
}
.neon{
    display: inline-block;
    color: #fff;
    letter-spacing: .05em;
    text-shadow: 0 1px 30px #1672fb, 0 0 12px #fff, 2px 5px 60px #077764;
}

.neon > span {
    -webkit-animation: blink 3s infinite alternate;
    animation: blink 3s infinite alternate;
  }
  @-webkit-keyframes blink {
    40% {
      opacity: .85;
    }
    42% {
      opacity: .4;
    }
    43% {
      opacity: .85;
    }
    45% {
      opacity: .4;
    }
    46% {
      opacity: .85;
    }
  }
  @keyframes blink {
    40% {
      opacity: .85;
    }
    42% {
      opacity: .4;
    }
    43% {
      opacity: .85;
    }
    45% {
      opacity: .4;
    }
    46% {
      opacity: .85;
    }
  }
</style>