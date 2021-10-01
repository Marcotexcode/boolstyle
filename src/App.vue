<template>
  
  <div id="app">
  
    <Header/>
    <Jumbotron/>
  
  </div>

</template>


<script>

  import Header from './components/Header.vue'
  import Jumbotron from './components/Jumbotron.vue'


  export default {

    name: 'App',

    components: {

      Header,
      Jumbotron

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
