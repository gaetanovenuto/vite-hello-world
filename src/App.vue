<script>
/* 
    Per importare ed utilizzare un componente dentro un altro devo SEMPRE seguire questi 3 passi:
    1) Importazione del componente
    2) Dichiarazione del componente
    3) Utilizzo del componente
*/


import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  data() {
    return {
      
    }
  },
  components: {
    AppTitle,
    AppHero
    }
}
</script>

<!-- All'interno del template ci va un solo elemento -->
<template>  
    <AppTitle />
    <AppHero />
</template>

<style scoped>
</style>
