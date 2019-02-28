<template>
  <div id="nav">
    <ion-grid>
      <div class="app-title">
        <ion-row>
          <ion-col size="12">
            <h1>Ionic - Vue.js</h1>
            <h3>An Ionic integration with Vue.js</h3>
          </ion-col>
        </ion-row>
      </div>
      <div class="logo">
        <ion-row>
          <ion-col size="12">
            <img src="https://raw.githubusercontent.com/dj0nny/ionic-vue/dev/src/assets/logo.png">
          </ion-col>
        </ion-row>
      </div>
      <ion-row>
        <ion-col size="12">
          <router-link to="/">Reddit's posts</router-link>|
          <router-link to="/about">About this repo</router-link>
        </ion-col>
      </ion-row>
      <router-view/>
    </ion-grid>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style lang="scss" scoped>
.logo {
  margin-top: -45px;
  img {
    width: 100%;
  }
}

#nav {
  padding: 0;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
