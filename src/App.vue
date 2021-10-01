<template>
  
  <div id="app">
  
    <Header/>
    <!-- <Sponsor/> -->

  
  </div>

</template>


<script>

  import Header from './components/Header.vue'
  //import Sponsor from './components/Sponsor.vue'



  export default {

    name: 'App',

    components: {

      Header,
     // Sponsor

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
