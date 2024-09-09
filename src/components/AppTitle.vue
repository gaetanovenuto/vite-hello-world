<script>

export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    }
  }
}
</script>

<!-- All'interno del template ci va un solo elemento -->
<template> 
  <div>
    <header>
        <h1> 
            {{ message }}
        </h1>
    </header>
  </div>
</template>

<style scoped>
header {
    padding: 25px 0;
    text-align: center;
}

</style>
