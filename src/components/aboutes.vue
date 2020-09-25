<template>
  <div class="about">
    <div data-aos="fade-right">
      <img class="profil" src="../assets/gambar/2.png" />
    </div>

    <div data-aos="fade-left">
      <h1>
        Hi, <br />
        I'am Risky Muhamad
      </h1>

      <p>
        A young technology enthusiast,<br />
        I am interested in the development of the<br />
        Website and graphic design.
      </p>

      <img class="kotak" src="../assets/gambar/3.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.about {
  margin: auto;
}
h1 {
  font-family: Montserrat;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 30px;
  text-align: left;
  padding-left: 10%;

  color: #000000;
}

p {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 15px;
  text-align: left;
  padding-left: 10%;
  color: #000000;

  margin-top: 24px;
  margin-bottom: 24px;
}

.profil {
  margin-top: 50px;
  margin-bottom: 20px;
  width: 199px;
  height: 253px;
}

.kotak {
  display: flex;
  align-content: flex-start;
  padding-left: 10%;
}
</style>
