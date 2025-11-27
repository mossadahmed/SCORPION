<!-- eslint-disable prettier/prettier -->
<template >
  <div class="home">
    <Nav />
    <router-view />
    <MyFooter />
  </div>
</template>
<script setup lang="ts">
import Nav from "./components/NavBar.vue";
import MyFooter from "./components/MyFooter.vue";
</script>

<style>
.home {
  background: url("/src/assets/Sections/WhatsApp%20Image%202025-11-27%20at%2020.32.57_002e1fe2.jpg");

}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fdfeff;

}
nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #ffffff;
}

nav a.router-link-exact-active {
  color: rgba(133, 133, 133, 0.904);
}
</style>
