<template lang="html">
  <div class="chat-log">
    <chat-message v-for="message in messages" :key="message" :message="message"></chat-message>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        messages: [
          {
              message: "Hi world",
              user: "migueref"
          },
          {
            message: "Hello Miguel",
            user: "migueref"
          }
        ]
      }
    }
  }
</script>
<style lang="css">

</style>
