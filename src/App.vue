<template>
  <div id="app">
    <Template />
  </div>
</template>

<script>
import Template from './components/Template'

export default {
  name: 'App',
  components: {
    Template
  }
}
</script>

<style lang="scss">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
</style>
