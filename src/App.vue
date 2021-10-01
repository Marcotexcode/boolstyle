<template>
  
  <div id="app">
  
    <Header/>
  
  </div>

</template>


<script>

  import Header from './components/Header.vue'


  export default {

    name: 'App',

    components: {

      Header

    }

  }

</script>


<style lang="scss">

  @import '@/style/general';
  @import '@/style/commons';

  .container-head {
    width: 100%;
    height: 1000px;
  }



</style>
