<template>
  <MyImage v-for="i in 2000" v-bind:key="i" v-bind:i="i"/>
</template>

<script>
import MyImage from "./components/MyImage";

export default {

  name: 'App',
  components: {
    MyImage
  },
  data() {
    return {
    };
  },
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
