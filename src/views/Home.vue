<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/Homes.vue";
import Footer from "@/components/footers.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Footer,
  },
};
</script>
