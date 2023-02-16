<template>
  <div class="box">
    <div class="wrapper">
      <div class="title">
        <h1>Cadastre-se</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque,
          odio. Eveniet commodi voluptate nihil architecto.
        </p>
      </div>
      <div class="form-box">
        <form action="#" class="form">
          <div class="inputContainer">
            <input type="text" class="input" placeholder="Nome Completo" />
            <label for="" class="label">Nome completo</label>
          </div>

          <div class="inputContainer">
            <input type="text" class="input" placeholder="E-mail" />
            <label for="" class="label">E-mail</label>
          </div>

          <div class="inputContainer">
            <input type="text" class="input" placeholder="Confirmar e-mail" />
            <label for="" class="label">Confirmar e-mail</label>
          </div>

          <div class="inputContainer">
            <input type="text" class="input" placeholder="CPF" />
            <label for="" class="label">Confirm Password</label>
          </div>
          <button type="submit">Continuar</button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactForm",

  data() {
    return {
      name: "",
      cpf: "",
      birthDate: "",
      email: "",
      confirmEmail: "",
    };
  },
};
</script>

<style scoped>
.box {
  width: 70%;
}

.wrapper {
  margin: 0 auto;
  height: 100%;
  width: 750px;
  padding: 1rem;
}

.title {
  display: flex;
  flex-direction: column;
  font-family: var(--font-poppins);
}

h1 {
  font-size: 2.4rem;
  color: var(--main-dark-low);
}

p {
  text-align: justify;
  font-size: 1rem;
  letter-spacing: 1px;
  max-width: 450px;
}

.title {
  font-size: 50px;
  margin-bottom: 50px;
}

.input-columns {
  position: relative;
  height: 45px;
  margin-bottom: 17px;
  font-family: var(--font-poppins);
}

.inputContainer {
  position: relative;
  height: 45px;
  width: 90%;
  margin-bottom: 17px;
  font-family: var(--font-poppins);
}

/* Style the inputs */

.input {
  position: absolute;
  top: 0px;
  left: 0px;
  height: 100%;
  width: 100%;
  background-color: #fff;
  border: 1px solid #DADCE0;
  border-radius: 7px;
  font-size: 16px;
  padding: 0.5rem;
  outline: none;
  z-index: 1;
}

/* Hide the placeholder texts (a) */

.input:focus::placeholder {
  color: transparent;
}

/* Styling text labels */

.label {
  position: absolute;
  top: 15px;
  left: 15px;
  padding: 0 4px;
  background-color: #fff;
  color: #DADCE0;
  font-size: 16px;
  z-index: 0;
}

.input:focus + .label {
  top: -10px;
  left: 12px;
  z-index: 10;
  font-size: 14px;
  font-weight: 600;
  color: var(--main-dark-low);
}

button {
  padding: 0.8rem 1rem;
  border: none;
  border-radius: 5px;
  background: #2b2323;
  color: #fff;
  font-weight: 700;
  font-family: var(--font-poppins);
  cursor: pointer;
}
</style>
