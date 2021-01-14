<template>
  <div id="app">
    <Container>
      <ChatMessage>sddsfdsf</ChatMessage>
      Hello, world
    </Container>
  </div>
</template>

<script>
import ChatMessage from './components/ChatMessage.vue'
import Container from './components/Container.vue'

export default {
  name: 'App',
  components: {
    Container,
    ChatMessage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
