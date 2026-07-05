<script setup>
    import {ref} from 'vue';
    const year = ref("2026") ;
</script>

<template>
    <p>@{{ year }}</p>
</template>

<style scoped>
    
  p {
      color: #4a5568;
      line-height: 1.5;
      margin: 1rem 0 0 0;
  }


</style>