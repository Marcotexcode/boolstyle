
<template>

    <div class="container-sponsor">
         
        <VueSlickCarousel class="cont-caro" v-bind="settings">
            
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
        
        </VueSlickCarousel>

        <!-- <div class="container-box">
            
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


        </div> -->
      
    </div>

</template>


<script>

    import VueSlickCarousel from 'vue-slick-carousel'
    import 'vue-slick-carousel/dist/vue-slick-carousel.css'
    import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

    export default {

        name: 'Sponsor',

        data() {

            return {

                settings: {

                    "infinite": true,
                    "slidesToShow": 3,
                    "slidesToScroll": 1,
                    "autoplay": true,
                    "arrows": true,
                    "speed": 8000,
                    "autoplaySpeed": 2000,
                    "responsive": [
                        
                        {
                            "breakpoint": 968,

                            "settings": {
                                "slidesToShow": 1,
                                "arrows": false,  
                            }

                        }

                    ]
          
                }
                
            }

        },

        components: { 

            VueSlickCarousel 

        }

    }

</script>


<style lang="scss" scoped>

    @import '@/style/variabili.scss';

    .container-sponsor {
        height: 100vh;
        
        .cont-caro {
            width: 90%;
            margin: 0 auto;
            display: flex;
        
            .box {
                padding: 50px;

                .container-box--img {
                    width: 100%;
                    height: 250px;
                    border-radius: 10px;
                    box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;

                }

                .container-description {
                    display: flex;
                    align-items: center;
                    justify-content: space-between;

                }

            }

            // .container-box {

            //     .box {

            //         height: 100%;
            //         border-radius: 20px;
            //         background: red;
            //         padding: 20px;
            //         margin: 5%;
            //     }

            // }

        }   


        // .container-box {
        //     width: 90%;
        //     padding-top: 100px;
        //     margin: 0 auto;
        //     display: flex;
        //     justify-content: space-between;


        // }
        // .box {
        //     width: 300px;
        //     border-radius: 20px;

        //     .container-box--img {
        //         width: 100%;
        //         height: 250px;
        //         border-radius: 10px;
        //         box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;

        //     }

        //     .container-description {
        //         display: flex;
        //         align-items: center;
        //         justify-content: space-between;

        //     }

        // }

    }




</style>