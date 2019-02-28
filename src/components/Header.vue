<template>
  <div id="nav">
    <ion-grid>
      <ion-row>
        <ion-col size="12">
          <router-link to="/">Reddit's posts</router-link>|
          <router-link to="/about">About this repo</router-link>
        </ion-col>
      </ion-row>
    </ion-grid>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style lang="scss" scoped>
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
