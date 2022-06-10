<template>
  <div class="container-footer">
    <div class="logo">
      <h1>Codar.</h1>
      <p>Criamos Websites Incriveis</p>
    </div>
    <div class="sobre">
      <h2>Sobre</h2>
      <p>
        Amamos criar soluções <br />
        e entregar sites incríveis
      </p>
    </div>
    <div class="contato">
      <h2>Contato</h2>

      <p>123 AV. Manjar - Nárnia</p>
      <p>+55 9 0000 - 0000</p>
      <li>contato@codar.com</li>
    </div>
    <div class="redes-sociais">
      <h2>Redes Sociais</h2>
      <i class="fa-brands fa-facebook-square"></i>
      <i class="fa-brands fa-instagram"></i>
      <i class="fa-brands fa-twitter-square"></i>
    </div>
  </div>
</template>

<script>
export default {
  nome: "Footer",
};
</script>

<style scoped>
.container-footer {
  text-align: left;
  background-color: black;
  color: white;
  display: flex;
  justify-content: space-around;
}

.redes-sociais i {
  color: #d6000d;
  font-size: 30px;
  margin: 10px;
}
li {
  list-style: none;
  margin-bottom: 5px;
}
@media only screen and (max-width: 600px) {
  .container-footer {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
