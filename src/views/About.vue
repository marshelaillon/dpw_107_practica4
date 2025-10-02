<template>
  <div class="about">
    <h1>Acerca de Nosotros: Este es un ejemplo</h1>
    <router-link to="/">Ir a Home</router-link>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style scoped>
.about {
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