<template>
12345
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script setup>
// eslint-disable-next-line no-unused-vars
import HelloWorld from './components/HelloWorld.vue'
import { ref } from "vue";

const drawerFlag = ref(false);
// eslint-disable-next-line no-unused-vars
const openDrawer = () => {
  drawerFlag.value = true;
};
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
