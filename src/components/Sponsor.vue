
<template>

    <div class="container-sponsor">
        
        <div class="container-box">
            
            <div class="box">

                <img class="container-box--img" src="../assets/house.jpg" alt="">

                <div class="container-description" >

                    <h2 class="container-description--title"> Titolo casa</h2>

                    <span class="container-description--price">Prezzo: 90€</span>

                </div>

                <span class="container-box--adress">Via</span>

            </div>

            <div class="box">

                <img class="container-box--img" src="../assets/house.jpg" alt="">

                <div class="container-description" >

                    <h2 class="container-description--title"> Titolo casa</h2>

                    <span class="container-description--price">Prezzo: 90€</span>

                </div>

                <span class="container-box--adress">Via</span>

            </div>

            <div class="box">

                <img class="container-box--img" src="../assets/house.jpg" alt="">

                <div class="container-description" >

                    <h2 class="container-description--title"> Titolo casa</h2>

                    <span class="container-description--price">Prezzo: 90€</span>

                </div>

                <span class="container-box--adress">Via</span>

            </div>


        </div>
      

    </div>


</template>


<script>

    export default {

        name: 'Sponsor',


    }

</script>



<style lang="scss" scoped>

    @import '@/style/variabili.scss';

    .container-sponsor {
        
        background-color: red;
        height: 100vh;
        margin-top: 73px;
        

        .container-box {

            width: 90%;
            padding-top: 50px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;


        }
        .box {
            width: 300px;
            border-radius: 20px;
            // box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;

            .container-box--img {
                width: 100%;
                height: 250px;
                border-radius: 20px;
            }

            .container-description {
                display: flex;
                align-items: center;
                justify-content: space-between;

            }

        }

    }




</style>