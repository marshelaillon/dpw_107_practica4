<template>
  <div class="home">
    <h1>Página de Inicio: Bienvenido!</h1>
    <router-link to="/about">Ir a About</router-link>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped>
.home {
  text-align: center;
  margin-top: 50px;
}

h1 {
  color: #42b983;
}

a {
  color: #42b983;
  text-decoration: none;
  font-size: 18px;
  margin-top: 20px;
  display: inline-block;
}

a:hover {
  text-decoration: underline;
}
</style>