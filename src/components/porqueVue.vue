<template>

<div class="porqueVue" id="porqueVue">

    <h3>¿Por qué Vue js?</h3>
    <p>
        La modularización de bibliotecas utilizando un marco es común en el desarrollo de frontend. Tanto React como Angular tienen modularización. Pero lo que diferencia a Vue.js de otras alternativas es su "alto desacoplamiento", lo fácil que es extender las funcionalidades y lo bien que funcionan todas las partes una vez que se incluyen más módulos. Por ejemplo, si queremos organizar y renderizar pequeños componentes visuales, todo lo que necesitamos es la biblioteca "central" de Vue.js; no es necesario incluir bibliotecas adicionales. A medida que la aplicación crece, tenemos bibliotecas para administrar rutas como "vue-router", bibliotecas para administrar el estado global como "vuex" o bibliotecas para crear aplicaciones web receptivas como "bootstrap-vue". Además, si nuestra aplicación necesita ser optimizada o necesita un buen SEO, podemos incluir la biblioteca "vue-server-rendering". En la siguiente figura podemos ver cómo se van incluyendo progresivamente las librerías que acabamos de mencionar, desde un pequeño SPA hasta aplicaciones multipágina (MPA
    </p>
</div>

</template>


<script>

  export default{
    name:'porqueVue'
  }

</script>

<style scoped>

.porqueVue{
    background-color: #00bbf0;
    padding-top: 2rem;
    padding-bottom: 2rem;
}



</style>