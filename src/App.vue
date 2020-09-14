<template>
  <div id="app">
    <h1>Guia de Clientes e Produtos </h1>
    <Cliente/>
    <produto/>
  </div>
  
</template>

<script>
import Cliente from './components/Cliente';
import Produto from './components/Produto';

export default {
  name: 'App',
  components: {
    Cliente,
    Produto
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
