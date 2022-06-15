<template>
  <nav-bar></nav-bar>
  <div class="app">
    <router-view></router-view>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar";

export default {
  components: {NavBar}
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Press Start 2P', cursive;
}
</style>