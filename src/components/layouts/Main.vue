<template>
  <div class="container-principal">
    <img src="@/assets/video_call.png" alt="" style="width: 250px" />
    <div class="container-lateral">
      <small>Avance seu negócio com um </small>
      <h1>Website incrível</h1>
      <button>Solicitar Orçamento</button>
    </div>
  </div>
  <div class="container-servicos">
    <div class="servicos">
      <ul class="lista-servicos">
        <li><i class="fa-solid fa-circle-check"></i> Dominio Personalizado</li>
        <li><i class="fa-solid fa-circle-check"></i> Hospedagem</li>
        <li><i class="fa-solid fa-circle-check"></i> Site Responsivo</li>
        <li><i class="fa-solid fa-circle-check"></i> Redes Sociais</li>
        <li><i class="fa-solid fa-circle-check"></i> Chat Online</li>
        <li><i class="fa-solid fa-circle-check"></i> Blog integrado</li>
        <div class="contato">
          <small>Nossa equipe está a disposição!</small><br />
          <input type="number" placeholder=" Celular" disabled="disabled" />
          <button>Ligamos pra Você</button>
        </div>
      </ul>

      <img
        class="img-servicos"
        src="@/assets/coding.png"
        alt=""
        style="width: 250px"
      />
    </div>
  </div>

  <div class="depoimentos">
    <div class="card">
      <div class="circle"></div>
      <div class="container-depoimentos">
        <p>
          já tive experiências com outras 4 empresas <br />
          e a Codar é sem sombra de dúvidas superior em todos aspectos!
        </p>
        <h3>Pedro Ferreira</h3>
        <small>Construtora Minari</small>
      </div>
    </div>

    <div class="card">
      <div class="circle"></div>
      <div class="container-depoimentos">
        <p>
          Processos bem simples e a criação de um site <br />
          como minha escola queria!
        </p>
        <h3>Maria Rita</h3>
        <small>Escola criança feliz</small>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style scoped>
.container-principal {
  display: flex;
  justify-content: space-around;
  gap: 30px;
  align-items: center;
}

.container-lateral h1 {
  margin-top: 0;
  color: #d6000d;
}

.servicos {
  margin-top: 200px;
  display: flex;
  justify-content: space-around;
  align-items: flex-end;
}

.lista-servicos {
  list-style: none;
  line-height: 30px;
}
.lista-servicos i {
  color: #d6000d;
}

.contato input {
  font-weight: 700;
  height: 30px;
  background-color: rgba(172, 169, 169, 0.5);
  color: white;
  border: none;
  border-radius: 10px;
  margin-right: 5px;
}
.depoimentos {
  margin-top: 150px;
  padding: 30px;
  display: flex;
  justify-content: space-evenly;
  align-content: itens;
}
.card {
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 12px;
  width: 450px;
  height: 150px;
  gap: 10px;
  background-color: rgba(172, 169, 169, 0.5);
  border-radius: 20px;
}

.circle {
  width: 60px;
  height: 60px;
  background-color: #d6000d;
  border-radius: 30.5px;
}
button {
  font-weight: 700;
  height: 30px;
  background-color: #d6000d;
  color: white;
  border: none;
  border-radius: 10px;
}
small {
  font-weight: 700;
}
h4 {
  margin-top: 0;
}

@media only screen and (max-width: 600px) {
  .servicos {
    margin-top: 100px;

    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column-reverse;
    order: 1;
  }
  .container-principal {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .depoimentos {
    margin-top: 100px;
    flex-direction: column;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .card {
    display: flex;
    text-align: center;
    margin-bottom: 20px;
    align-items: center;
    justify-content: center;
    font-size: 10px;
    width: 300px;
    height: 150px;
    background-color: rgba(172, 169, 169, 0.5);
    border-radius: 20px;
  }

  .circle {
    width: 60px;
    height: 60px;
    background-color: #d6000d;
    border-radius: 30.5px;
  }
}
</style>
