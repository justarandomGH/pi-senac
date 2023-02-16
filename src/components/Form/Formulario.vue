<template>
  <div>
    <header>
      <img src="https://cdn-icons-png.flaticon.com/512/507/507257.png" alt="" />
      <img src="https://cdn-icons-png.flaticon.com/512/860/860790.png" alt="" />
    </header>
  </div>
</template>

<script>
export default {
  name: "Formulario",
};
</script>

<style scoped>
</style><template>
  <div>
    <HeaderForm />
    <div class="form-box">
      <Background />
      <ContactForm />
    </div>
  </div>
</template>

<script>
import HeaderForm from "./HeaderForm.vue";
import ContactForm from "./ContactForm.vue";
import Background from "./Background.vue";
export default {
  name: "Formulario",

  components: {
    HeaderForm,
    Background,
    ContactForm,
  },
};
</script>

<style scoped>
.form-box {
  display: flex;
}
</style>
