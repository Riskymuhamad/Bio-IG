<template>
  <div class="Blog">
    <h1>Sorry, the Blog view is still under <span>Development</span></h1>
    <HelloWorld />
    <Footer />
  </div>
</template>

<script>
import Footer from "@/components/footers.vue";
import HelloWorld from "@/components/Homes.vue";

export default {
  name: "About",
  components: {
    HelloWorld,
    Footer,
  },
};
</script>

<style scoped>
h1 {
  font-family: Montserrat-Bold;
  color: #000000;

  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 22px;
  text-align: left;
  padding-left: 10%;
  padding-right: 10%;
  letter-spacing: 0.03em;

  margin-top: 88px;
}
span {
  color: red;
}
</style>

