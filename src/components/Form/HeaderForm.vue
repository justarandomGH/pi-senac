<template>
  <header>
    <!-- <h2 class="senac">Senac</h2>
    <h2 class="fit">FIT</h2> -->
    <h2>Nome</h2>
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

.senac {
  font-family: var(--font-poppins);
  font-size: 2rem;
  font-weight: 700;
  color: var(--main-dark);
  letter-spacing: 1px;
}

.fit {
  font-family: var(--font-lato);
  font-size: 2.1rem;
  font-weight: 700;
  color: var(--main-orange);
  letter-spacing: 2px;
}
</style>
