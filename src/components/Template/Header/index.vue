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

<style lang="scss">
  
  .header {
    display: flex;
    top: 0;
    width: 100%;
    height: $header-height;
    border-bottom: 2px solid $bg-color-dark-gray;
    color: $font-color;
    
    &__channels {
      background-color: $bg-color-gray;
      width: 15%;
      height: 100%;
    }

    &__chat {
      background-color: $bg-color-light-gray;
      width: 85%;
      height: 100%;
    }
  }
</style>