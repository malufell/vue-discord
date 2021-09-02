<template>
  <div class="server-item">
    <img class="server-item__img" src="https://via.placeholder.com/150/4aa286">
    <img class="server-item__img" src="https://via.placeholder.com/150/eacc86">
    <img class="server-item__img" src="https://via.placeholder.com/150/416ca7">
    <img class="server-item__img" src="https://via.placeholder.com/150/b3db9a">
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">

  .server-item {
    @include alignFlex(column, center);

    &__img {
      @include boxIconServer();
    }

    &__img:hover{
      transition: 200ms;
      border-radius: 35%;
    }
  } 

</style>