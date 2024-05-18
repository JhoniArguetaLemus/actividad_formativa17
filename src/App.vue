<template>
 
  <barra/>
  <contenido/>
  <porqueVue/>
  <misDatos/>
</template>

<script>

import barra from './components/barra.vue'
import contenido from './components/contenido.vue'; 
import porqueVue from  './components/porqueVue.vue';
import misDatos from './components/misDatos.vue';
export default {
  name: 'App',
  components: {

    barra,
    contenido,
    porqueVue,
    misDatos
  }
}
</script>

<style>

*{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
 
}
</style>
