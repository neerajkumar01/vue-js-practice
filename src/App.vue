<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <!-- <Home propname="hello this is prop" /> -->
    <!-- <Home proptwo="this is second prop" /> -->
    <!-- <Fordirective /> -->
    <!-- <Signup /> -->
    <!-- <SignUpTwo /> -->
    <!-- <FileExplore /> -->
    <ApiFileThis />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
// import Home from "./components/Home.vue";
// import Fordirective from "./components/Fordirective.vue";
// import Signup from "./components/Signup.vue";

// import SignUpTwo from "./components/SignUpTwo.vue";
// import FileExplore from "./components/FileExplore.vue";
import ApiFileThis from "./components/ApiFileThis.vue";
export default {
  name: "App",
  components: {
    ApiFileThis,
    // HelloWorld,
    // Home,
    // Fordirective,
    // Signup,
    // SignUpTwo,
    // FileExplore,
  },
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
