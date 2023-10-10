<template>
  <div id="app">
    <landingPage></landingPage>
  </div>
</template>

<script>
  import landingPage from './views/landingPage.vue';
  export default {
    components: {
      landingPage
    }
  }
</script>

<style>
* { 
   margin: 0;
   padding: 0;
   list-style: none;
   text-decoration: none;
   box-sizing: border-box;
} 
</style>
