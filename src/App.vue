<script>

import Navbar from "./components/navigation.vue";
import Home from "./components/home.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Home
  },
};

</script>

<template>

    <div id="app">
      <Navbar/>
      <Home />
      <Option />
    </div>

</template>