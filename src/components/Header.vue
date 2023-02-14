<template>
  <div class="header-wrapper">
    <header>
      <div class="logo">
        <span class="senac">Senac</span><span class="fit">FIT</span>
      </div>
      <nav>
        <ul>
          <li>Sobre</li>
          <li>Objetivos</li>
          <li>Inscrever-se</li>
          <li>Contato</li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
header {
  display: flex;
  align-items: center;
  justify-content: space-around;
  padding: 1.5rem;
  background: var(--main-white);
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

ul {
  display: flex;
  gap: 3.5rem;
}

li {
  font-family: var(--font-montserrat);
  padding: 0.8rem;
  font-size: 1.1rem;
  font-weight: 700;
  color: rgba(0, 0, 0, 0.8);
  border-radius: 5px;
  cursor: pointer;
  transition: 200ms;
}

li:hover {
  background: #c9d6d4;
  color: rgba(0, 0, 0, 0.7);
}
</style>