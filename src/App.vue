<template>
  <div id="app">
    <headerMain></headerMain>
    <modalComponent></modalComponent>

    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import headerMain from "@/components/headerMain/headerMain.vue";
import footerMain from "@/components/footerMain/footerMain.vue";
import modalComponent from "@/components/modalComponent/modalComponent.vue"

export default {
  name: "app",
  components: {
    HelloWorld,
    headerMain,
    modalComponent,
    footerMain
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: auto;
}

#footer {
  margin-bottom: 0%
}
</style>
