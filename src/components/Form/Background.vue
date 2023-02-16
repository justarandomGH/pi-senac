<template>
  <div class="background"></div>
</template>

<script>
export default {
  name: "Background",
};
</script>

<style scoped>
.background {
  display: flex;
  align-items: center;
  justify-content: space-around;
  height: 93vh;
  width: 50%;
  background-image: linear-gradient(to right, #423c3c66, #3d373766),
    url("https://images.unsplash.com/photo-1560233075-4c1e2007908e?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2030&q=80");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  box-shadow: 2px 1px 5px rgba(0, 0, 0, 0.3);
}
</style>
