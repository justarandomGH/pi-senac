<template>
  <section class="banner">
    <div class="about">
      <h1>Title Here</h1>
      <p>
        <!-- <img src="https://cdn-icons-png.flaticon.com/512/2985/2985162.png" alt=""> -->
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus
        similique delectus officiis doloremque excepturi veritatis tempora eum
        dolore distinctio, sed saepe quidem dolores odit illum eos deleniti
        quisquam omnis exercitationem libero. Aspernatur et recusandae aperiam,
        expedita nisi vel totam voluptatibus quisquam optio. Recusandae esse
        excepturi illo ratione, fugiat omnis quo?
      </p>
    </div>
    <div class="banner-button-box">
      <button>Inscrever-se</button>
    </div>
  </section>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
.banner {
  display: flex;
  align-items: center;
  justify-content: space-around;
  height: 91vh;
  background-image: linear-gradient(
      to right,
      rgba(129, 122, 122, 0.4),
      rgba(122, 120, 120, 0.3)
    ),
    url("https://images.unsplash.com/photo-1553012547-284d8c582b1f?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.about {
  padding: 2rem 1rem;
  min-height: 40%;
  max-width: 650px;
  border: none;
  border-radius: 5px;
}

.about h1 {
  font-family: var(--font-lato);
  font-size: 3rem;
  color: var(--main-dark);
}

.about p {
  font-size: 1.2rem;
  text-align: justify;
  color: var(--main-white);
  font-family: var(--font-roboto);
}

.banner button {
  padding: 1rem 2rem;
  border: none;
  border-radius: 5px;
  font-family: var(--font-poppins);
  font-size: 1.1rem;
  font-weight: 700;
  background: var(--main-dark-low);
  color: var(--main-white);
  cursor: pointer;
  transition: 200ms;
}

.banner button:hover {
  padding: 1rem 2.5rem;
  background: var(--main-dark);
}
</style>
