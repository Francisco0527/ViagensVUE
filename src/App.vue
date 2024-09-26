<template>
  <div id="app">
    <img alt="logo" src="./assets/logo.png" />
    <h1>Lugares</h1>
    <Menu @city-selected="city = $event" />
    <component :is="currentCityComponent"></component>
  </div>
</template>

<script>
import Menu from "./components/Menu.vue";
import Paraty from "./components/Paraty.vue";
import Campos from "./components/Campos.vue";
import Gramado from "./components/Gramado.vue";

export default {
  components: {
    Menu,
    Paraty,
    Campos,
    Gramado,
  },
  data() {
    return {
      city: "Cidades", // Cidade padrão exibida ao iniciar
    };
  },
  computed: {
    currentCityComponent() {
      return this.city;
    },
  },
};
</script>
<style>
* {
  padding: 0;
  margin: 0;
}
body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background-image: url("/src/assets/background.jpg");
  background-size: cover;
  background-position: 0;
  background-repeat: no-repeat;
  background-attachment: fixed;
  height: 100vh;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #d4d2d2;
  /* overflow: hidden; */
}
</style>
<style scoped>
img {
  height: 80px;
  margin-top: 5px;
}
h1 {
  font-size: 36px;
}
</style>
