<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/blog">Blog</router-link>
      <router-link to="/contact">Contact</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

@font-face {
  font-family: "neucha";
  src: local("neucha"), url(assets/font/neucha.otf) format("truetype");
}

@font-face {
  font-family: "Montserrat-Bold";
  src: local("Montserrat-Bold"),
    url(assets/font/Montserrat-Bold.ttf) format("truetype");
}

@font-face {
  font-family: "Montserrat-Regular";
  src: local("Montserrat-Regular"),
    url(assets/font/Montserrat-Regular.ttf) format("truetype");
}

#nav {
  padding-top: 33px;
  font-family: neucha;
  font-size: 18px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  margin: 0 25px;
}

#nav a.router-link-exact-active {
  color: red;
}
</style>
