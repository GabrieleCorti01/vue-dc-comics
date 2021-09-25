
<template>
    <main>
<!-- Content goes here -->
        <section class="main-1">
            <h1>-- Content goes here --</h1>
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
export default {
    name: "Main",
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

main{
    background-color: $secondaryColor;
}

.main-1{
    padding: 30px;
    color: $thirdColor;
    display: flex;
    align-items: center;
}

h1{
    font-weight: 600;
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