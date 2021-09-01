<template>
  <header class="header">

    <div class="header__channels">
      header
    </div>

    <div class="header__chat">
      header 
    </div>

  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
  
  .header {
    display: flex;
    top: 0;
    width: 100%;
    height: 48px;
    border-bottom: 2px solid #202225;
    color: #ffffff;

    &__channels {
      background-color: #2f3136;
      width: 15%;
      height: 100%;
    }

    &__chat {
      background-color: #36393f;
      width: 85%;
      height: 100%;
    }
  }
</style>