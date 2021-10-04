<template>
  
  <div class="container">

      <div class="close">&times;</div>
      
    <h2>Login</h2>

    <div class="form-element">

        <label for="email">Email</label>
        <input type="text" id="email" placeholder="Inserisci email">

    </div>

    <div class="form-element">

        <label for="password">Password</label>
        <input type="password" id="password" placeholder="Inserisci password">

    </div>

    <div class="form-element">

        <button>Enter</button>

    </div>


  </div>

</template>

<script>
export default {

    name: 'Login',

    data() {
            
            return {
            
                ActiveLog: false


            }
        
        },

}
</script>

<style lang="scss" scoped>

    @import '@/style/variabili.scss';


    .container {
        width: 20%;
        top: 200%;
        left: 40%;
        position: absolute;
        background: $BgcHeader;
        color: $ColorText1;
        border-radius: 20px;
        padding: 40px;

        .form-element {
            margin: 20px 0px;

        }

    }


</style>