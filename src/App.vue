<template>
  <div id="app">

    <Header :menuItems='menuItems'/>

    <Main />

    <Footer />

  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {

  name: "App",

  components: {
    Header,
    Main,
    Footer,
  },

  data: function() {
    return {
      menuItems: ['Home', 'About', 'Projects', 'Services', 'Blog', 'Contact'],
    }
  }
};
</script>

<style lang="scss">

@import "./styles/general.scss"


</style>
