<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
// Styles global for site...
import "./styles/global.css";

//Import components for site...
import Header from "./components/Header/Header";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style></style>
