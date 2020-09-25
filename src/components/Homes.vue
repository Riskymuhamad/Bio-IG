<template>
  <div class="hello" data-aos="zoom-in-up">
    <img alt="development" src="../assets/gambar/1.png" />

    <p>Thank you for visiting :)</p>
  </div>
</template>

<script>
export default {
  name: "Homes",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
img {
  margin-top: 36px;
  width: 263px;
  height: 197px;
}

p {
  font-family: Montserrat-Regular;
  margin-top: 88px;

  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 15px;
  /* identical to box height */

  text-align: center;
}
</style>
