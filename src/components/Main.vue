
<template>
    <main>

<!-- Jumbotron image -->
        <section class="jumbotron-img">

        </section>

<!-- Content goes here -->  
        <section class="main-1">
            <div class="container-film">
                <FilmSeries v-for="(element, index) in filmElements" :key="index" :title="element.series" :src="element.thumb"/>
            </div>

            <div class="container-button-load">
                <input type="button" value="SIGN-UP NOW!" class="button-load-more" onclick="msg()"> 
            </div>
        </section>

<!-- List icon main -->
        <section class="main-2">
            <ul>
                <li>
                    <img src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="img-digital-comics">
                    <a href="#">DIGITAL COMICS</a>
                </li>

                <li>
                    <img src="../assets/vue-dc-comics-1/img/buy-comics-merchandise.png" alt="img-merchandise">
                    <a href="#">DC MERCHANDISE</a>
                </li>

                <li>
                    <img src="../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="img-subscriptions">
                    <a href="#">SUBSCRIPTION</a>
                </li>

                <li>
                    <img src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="img-shop-locator">
                    <a href="#">CMOMC SHOP LOCATOR</a>
                </li>

                <li>
                    <img src="../assets/vue-dc-comics-1/img/buy-dc-power-visa.svg" alt="img-power-visa">
                    <a href="#">DC POWER USA</a>
                </li>

            </ul>
        </section>


    </main>
</template>

<script>

import FilmSeries from "./FilmSeries.vue";
import filmElements from "../data/filmElements.js"

export default {

    name: 'Products',

    components: {
    FilmSeries,
    },
    data: function (){
        return {
            filmElements,
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

main{
    background-color: $secondaryColor;
}

.jumbotron-img{
    height: 450px;
    background-image: url(../assets/vue-dc-comics-1/img/jumbotron.jpg);
}

.main-1{
    padding: 30px;
    color: $thirdColor;
}

.container-film{
    flex-wrap: wrap;
    display: flex;
    padding: 20px;
}

h1{
    font-weight: 600;
}

.container-button-load{
    display: flex;
    justify-content: center;
}

.button-load-more{
    padding: 10px 40px;
    border: none;
    background-color: $primaryColor;
    color: $thirdColor;
    font-weight: 600;
    font-size: 0.9em;
}

.main-2{
    background-color: $primaryColor;
    display: flex;
    justify-content: center;

}

ul{
    display: flex;
    list-style: none;
}

ul li{
    padding-left: 60px;
}

li a{
    color: $thirdColor;
    padding: 20px;
    text-decoration: none;
}

li img{
    height: 60px;
    vertical-align: middle;
    padding-top: 40px;
    padding-bottom: 40px;
}


</style>