<template>
  <div id="app" class="bg-wwpink flex justify-center">
    <div class="flex flex-column">
      <WwHeader></WwHeader>
      <div class="pa2"></div>
      <WwContent></WwContent>
    </div>
  </div>
</template>

<script>
import WwHeader from "./components/header"
import WwContent from "./components/content"
export default {
  name: 'App',
  components: {
    WwHeader,
    WwContent
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
  height: 100%;
  width: 100%;
}
</style>
