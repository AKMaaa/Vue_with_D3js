<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HeaderShow msg="unko"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <WordCloud />
</template>

<script>
// ここでコンポーネントをインポートする
import HelloWorld from './components/HelloWorld.vue'
import WordCloud from './components/WordCloud.vue'
import HeaderShow from './components/HeaderShow.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    WordCloud,
    HeaderShow
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
