<template>
  <img alt="my_photo" src="./assets/IMG_9393 2.png">
  <GreetingsMessage msg="Welcome to my portfolio site"/>
</template>

<script>
import GreetingsMessage from './components/Greeting.vue'

export default {
  name: 'App',
  components: {
    GreetingsMessage
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

img {
  border-radius: 50%; /* 画像を円形にする */
  width: 100px; /* 画像の幅を100pxに設定 */
  height: 100px; /* 画像の高さを100pxに設定 */
  object-fit: cover; /* 画像の比率を保ちつつ、設定した領域に収める */
}
</style>
