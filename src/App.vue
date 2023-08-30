<template>
  <CenaVisigodo />
</template>

<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import CenaVisigodo from './components/CenaVisigodo.vue'

</script>


<style scoped>
.container {
  text-align: center;
  max-width: 800px;
  /* Establece un ancho máximo para evitar que el contenido se vuelva demasiado ancho en pantallas grandes */
  margin: 0 auto;
  /* Centra el contenido horizontalmente */
  padding: 20px;
}

/* Media Query para pantallas más pequeñas */
@media (max-width: 600px) {
  .container {
    padding: 10px;
    /* Reduce el espacio interno en pantallas pequeñas */
  }

  .oferta img {
    width: 45px;
    /* Reduce el tamaño de la imagen de oferta en pantallas pequeñas */
  }
}

/* Media Query para pantallas medianas */
@media (min-width: 601px) and (max-width: 1200px) {
  .container {
    padding: 15px;
    /* Ajusta el espacio interno en pantallas medianas */
  }
}</style>
