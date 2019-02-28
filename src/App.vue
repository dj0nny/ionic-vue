<template>
  <div id="app">
    <Header/>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  components: {
    Header
  }
};
</script>

<style lang="scss">
h1 {
  margin: 0;
}

#app {
  font-family: "Montserrat", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
