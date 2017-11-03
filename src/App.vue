<template>
  <div id="app">
    <h4>分页组件</h4>
    <pagination :pageNumber="12" :curNumber="5" :showNumber="5"></pagination>
    <pagination :pageNumber="12" :curNumber="5" :showNumber="3"></pagination>
  </div>
</template>

<script>
import pagination from './components/pagination'

export default {
  name: 'app',
  components: {
    pagination
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
