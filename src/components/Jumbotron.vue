<template>
    <div class="jumbotron">
        <form class="example" action="/action_page.php" style="margin:auto;max-width:300px">
            <input type="text" placeholder="Search.." name="search2">
            <button type="submit"><i class="fa fa-search"></i></button>
        </form>
    </div>
</template>

<script>

export default {

    name: 'Jumbotron',

    data() {
        
        return {
        
            isActive: false

        }
    
    },

    methods: {

        myFilter: function() {

            this.isActive = !this.isActive;

        }

    }

}

</script>

<style lang="scss" scoped>

    @import '@/style/variabili.scss';

    .jumbotron {
        background-image: url("../assets/apart.jpg");
        background-size: cover;
        height: 500px;
    }

    form.example input[type=text] {
        padding: 10px;
        font-size: 17px;
        border: 1px solid grey;
        float: left;
        width: 80%;
        background: #f1f1f1;
    }

    form.example button {
        float: left;
        width: 20%;
        padding: 10px;
        background: #2196F3;
        color: white;
        font-size: 17px;
        border: 1px solid grey;
        border-left: none;
        cursor: pointer;
    }

    form.example button:hover {
        background: #0b7dda;
    }

    form.example::after {
        content: "";
        clear: both;
        display: table;
    }

</style>
