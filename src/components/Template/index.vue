<template>
  <div class="template">
    <MenuServers />
    <Content />
  </div>
</template>

<script>
import MenuServers from './MenuServers'
import Content from './Content'

export default {
  components: {
    MenuServers,
    Content,
  }
}
</script>

<style lang="scss">

  .template {
    display: flex;  
  }

</style>