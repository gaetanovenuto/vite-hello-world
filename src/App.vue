<script>
/* 
    Per importare ed utilizzare un componente dentro un altro devo SEMPRE seguire questi 3 passi:
    1) Importazione del componente
    2) Dichiarazione del componente
    3) Utilizzo del componente
*/

import AppHeader from './components/AppHeader.vue';

export default {
  data() {
    return {
      
    }
  },
  components: {
    AppHeader
    }
}
</script>

<!-- All'interno del template ci va un solo elemento -->
<template> 
  <div>
    <AppHeader />
    <h1> 
      
    </h1>
  </div>
</template>

<style scoped>
</style>
