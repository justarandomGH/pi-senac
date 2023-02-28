<template>
  <header>
    <!-- <h2 class="senac">Senac</h2>
    <h2 class="fit">FIT</h2> -->
    <span class="m">M</span>
    <span class="y">y</span>
    <h2>Health</h2>
    <button>
      <img src="https://cdn-icons-png.flaticon.com/512/507/507257.png" alt="" />
    </button>
  </header>
</template>

<script>
export default {
  name: "HeaderForm",
};
</script>

<style scoped>
header {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1.5rem;
  background: #d1ebe9;
  box-shadow: 1px 2px 2px rgba(0, 0, 0, 0.5);
  font-family: var(--font-montserrat);
}

img {
  width: 1.4rem;
}

button {
  background: transparent;
  border: none;
  position: absolute;
  left: 2rem;
}

.m {
  font-family: var(--font-poppins);
  font-size: 2rem;
  font-weight: 700;
  letter-spacing: 1px;
}

.y {
  font-family: var(--font-lato);
  font-size: 2.3rem;
  font-weight: 700;
  letter-spacing: 2px;
}

h2 {
  text-transform: uppercase;
  letter-spacing: 1px;
  font-size: 1.2rem;
}
</style>
