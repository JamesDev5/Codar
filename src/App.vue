<template>
<Header/>
</template>

<script>
import Header from "@/components/layouts/Header.vue"
export default {
  name: "App",
  components: {
    Header
  },
};
</script>

<style>
  body{
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');
    font-family: 'Roboto', sans-serif;
    font-size: 14px;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>
