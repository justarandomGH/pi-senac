<template>
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
