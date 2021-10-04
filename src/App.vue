<template>
  
  <div id="app">
  
    <Header/>

    <Jumbotron/>

    <Sponsor/>

    <Banner/>

    <Footer/>


  
  </div>

</template>


<script>

  import Header from '@/components/Header.vue'
  import Sponsor from '@/components/Sponsor.vue'
  import Jumbotron from '@/components/Jumbotron.vue'
  import Banner from '@/components/Banner.vue'
  import Footer from '@/components/Footer.vue'




  export default {

    name: 'App',

    components: {

      Header,
      Jumbotron,
      Sponsor,
      Banner,
      Footer

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
