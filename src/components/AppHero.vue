<script>

export default {
  data() {
    return {
      image: '../vite.svg'
    }
  }
}
</script>

<!-- All'interno del template ci va un solo elemento -->
<template> 
  <div>
    <div class="jumbotron">
        <img :src="image" alt="Vue">
    </div>
  </div>
</template>

<style scoped>
    .jumbotron {
      display: flex;
      justify-content: center;
    }
    
    .jumbotron img {
      height: 350px;
    }
</style>
