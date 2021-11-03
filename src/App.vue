<template>
  <div class="container mt-4">
    <HttpAxios />
    <HttpFetch />
  </div>
</template>

<script>
  import HttpAxios from './components/HttpAxios'
  import HttpFetch from './components/HttpFetch'

  export default {
    name: 'App',
    components: {
      HttpAxios,
      HttpFetch
    }
  }
</script>

<style>
   .container {
      max-width: 500px;
   }
</style>


