<template>
  <header>
      <h1>Nuxt.JS Poc</h1>
      
      <HeaderLinks />
  </header>
</template>

<script>
  import HeaderLinks from './headerLinks'

  export default {
    components: {
      HeaderLinks
    } 
  }
</script>


<style scoped>
  header {
    border: 1px solid rgba(0, 0, 0, 0.5);
    text-align: center;
    padding: 20px;
    font-family: "Arial";
    box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.5);
  }
</style>