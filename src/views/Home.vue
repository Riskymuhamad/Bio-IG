<template>
  <div class="home">
    <Aboutes />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Aboutes from "@/components/aboutes.vue";
import Footer from "@/components/footers.vue";

export default {
  name: "Home",
  components: {
    Footer,
    Aboutes,
  },
};
</script>
