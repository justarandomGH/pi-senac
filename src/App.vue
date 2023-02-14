<template>
  <Formulario />
</template>

<script>
// import Header from "./components/Header.vue";
// import Banner from "./components/Banner.vue";
// import Objetivos from "./components/Objetivos.vue";
import Formulario from "./components/Form/Formulario.vue";
export default {
  name: "App",
  components: {
    Formulario,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lato&family=Montserrat:wght@300;400;500;700&family=Poppins:wght@200;300;400;500;700&family=Roboto:wght@400;500&display=swap");

:root {
  --font-poppins: "Poppins", sans-serif;
  --font-lato: "Lato", sans-serif;
  --font-montserrat: "Montserrat", sans-serif;
  --font-roboto: "Roboto", sans-serif;
  --main-blue: hsl(217, 64%, 31%);
  --main-orange: hsl(45, 100%, 50%);
  --main-dark: hsl(210, 32%, 9%);
  --main-dark-low: hsla(0, 0%, 0%, 0.8);
  --main-white: hsl(180, 22%, 90%);
  --primary-cream: hsl(52, 19%, 85%);
}

html {
  scroll-behavior: smooth;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
}

body {
  background: var(--main-white);
}

.header-wrapper {
  margin: 0 auto;
  width: 1450px;
}
</style>
