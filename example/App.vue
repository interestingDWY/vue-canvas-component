<template>
  <vue-canvas-nest></vue-canvas-nest>
</template>

<script>
import vueCanvasNest from '../src/vueCanvasNest'
export default {
  name: 'app',
  components: { vueCanvasNest },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      config: {
        color:'100,100,255',
        count: 200,
      }
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
