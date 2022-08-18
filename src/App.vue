<template>
  <h1>字 ↔️ 😀</h1>
  <Main/>
</template>

<script>
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Main
  }
}
</script>

<style>
h1 {
  margin-top: 0;
  height: 40px;
  padding: 10px 10px 10px 10px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100%;
  /* margin: 0 10px; */
  /* flex布局让块垂直居中 */
  align-items: center;
}
</style>
