<template>
  <Header />
  <Main />
  <Footer />
</template>

<script>
import Header from "@/components/layouts/Header.vue";
import Main from "@/components/layouts/Main.vue";
import Footer from "@/components/layouts/Footer.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style>
body {
  @import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap");
  font-family: "Roboto", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
