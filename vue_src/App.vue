<template>
  <div id="app">
    Yahoo
    {{count}}
    <button @click="count = count + 1">+</button>
    <button @click="count = count - 1">-</button>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      count: 0
    }
  }
}
</script>

<style lang="scss">
</style>
