<template lang='pug'>
<div id="app">
    div 路由列表：
    a(href='/') highlight
    <br/>
    router-link(to='/hello') hello
    div ----下面是内容-----
    <router-view/>
</div>
</template>

<script>
export default {
    name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
