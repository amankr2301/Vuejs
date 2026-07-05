<script setup>
    import {ref} from 'vue'; 
    const emoji = ref("👋");

</script>

<template>
    <span>{{ emoji }}</span>
</template>

<style scoped>
    span {
    font-size: 3rem;
    margin-bottom: 0.5rem;
    display: inline-block; 
}
</style>