<script setup>
  import { ref } from 'vue';
  import Header from './components/header.vue';
  import Main from './components/main.vue';
  import Footer from './components/footer.vue';
</script>

<template>
  <div class="screen-wrapper">   
    <div class="card">
      
      <Header />
      <Main /> 
      <Footer />
    </div>

  </div>
</template>



<style scoped>
 
  .screen-wrapper {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: rgba(249, 250, 11, 0.06);
      font-family: system-ui, -apple-system, sans-serif;
  }

  /* The actual card box design */
  .card {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      width: 90%; /* Responsive scaling for mobile */
      max-width: 400px;
      padding: 2rem;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
      border: 1px solid whitesmoke;
  }


</style>