<template>
  <div>
    {{bzk}}
    <test/>
  </div>
</template>

<script>
  import Test from '../test/test.js'
  export default {
    name: 'App',
    components: {
      Test
    },
    data(){
      return {
          bzk: '凌影'
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
</style>
