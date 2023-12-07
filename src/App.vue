<template>
  <div id="app">
    <ChatBox />
    <ChatBoxOG />
  </div>
</template>

<script>
import ChatBox from './components/ChatBox.vue';
import ChatBoxOG from "./components/ChatBoxOG.vue";

export default {
  name: 'App',
  components: {
    ChatBox,
    ChatBoxOG,
  },
};
</script>

<style scoped>

#app{
  display: flex;
  flex-direction: row;
  height: 95vh;
  width: 95vw;
  margin: 0;
}

</style>