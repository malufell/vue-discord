<template>
  <div class="menu-servers">
    <ServerList />
  </div>
</template>

<script>
import ServerList from "../../shared/ServerList"

export default {
  components: {
      ServerList,
  },
}
</script>

<style lang="scss">
  
  .menu-servers {
    @include alignFlex(column, start);
    width: auto;
    height: 100vh;
    background-color: $bg-color-dark-gray;  
  }
</style>