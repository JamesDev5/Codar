<template>
<nav class="container-topo">
    <h1 >Codar.</h1>
  <ul class="menu-navigation">
    <li><a href="home">Inicio</a></li>
    <li><a href="services">Serviços</a></li>
    <li><a href="contact">Contatos</a></li>
    <button class="btn-login">Login</button>
  </ul>
</nav>
</template>

<script>
export default {
      name:"Header"
}
</script>

<style scoped>
.container-topo{
  margin: 20px ;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.menu-navigation{
  display: flex;
  justify-content: flex-end;
  align-items: center;

  gap: 20px;
  font-weight: 700;
}
h1{
  color:#D6000D;
}
li{
  list-style: none;
  
}
a{
  text-decoration: none;
  color: black;
}
.btn-login{
  font-weight: 700;
  width: 100px;
  height: 30px;
  background-color: #D6000D;
  color: white;
  border: none;
  border-radius: 10px;
}

</style>