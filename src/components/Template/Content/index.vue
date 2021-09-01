<template>
  <div class="content">

    <Header />

    <div class="content__areas">
      <Channels />
      <Chat />
      <Users />
    </div>
    
  </div>
</template>

<script>
import Header from '../Header'
import Channels from '../Channels'
import Chat from '../Chat'
import Users from '../Users'

export default {
  components: {
    Header,
    Channels,
    Chat,
    Users
  }
}
</script>

<style lang="scss">

  .content {
    display: flex; 
    flex-direction: column;
    width: 95%; 

    &__areas {
      display: flex; 
      height: calc(100vh - 48px);
   }
  }


</style>