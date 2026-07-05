<script setup>
    import {ref} from 'vue';
    const name = ref("Aman") ; 
</script>

<template>
    <h1>{{ name }}</h1>
</template>

<style scoped>
    
  h1 {
      font-size: 4rem;
      margin: 0;
      color: #e53e3e; 
  }

</style>