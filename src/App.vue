<template>
  <div id="app">
    <transition name="slide">
      <router-view/>
    </transition>
  </div>
</template>

<script>

export default {
  name: 'App',
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color:white;
}
</style>
