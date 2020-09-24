<template>
  <div class="hello">
    <h1>
      Mohon Maaf Website Masih <br />
      Dalam <span>Pengembangan</span>
    </h1>

    <img alt="Vue logo" src="../assets/gambar/1.png" />

    <p>Terima Kasih, Telah Berkunjung :)</p>
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
h1 {
  font-family: Montserrat-Bold;

  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  letter-spacing: 0.03em;

  margin-top: 88px;
}

img {
  margin-top: 36px;
  width: 263px;
  height: 197px;
}

span {
  color: red;
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
