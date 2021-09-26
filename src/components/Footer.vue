
<template>
    <footer>
        <section class="jumbotron">
            
    <!-- CONTAINER LISTA 1 -->
            <div class="container-lista">
                <ul>
                    <li>
                        <h2>DC COMICS</h2>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>
                </ul>

                <ul>
                    <li>
                        <h2>DC COMICS</h2>
                    </li>

                    <li>
                        <a href="#">Shop DC</a>
                    </li>

                    <li>
                        <a href="#">Shop DC Collectibles</a>
                    </li>
                </ul>
            </div>

    <!-- CONTAINER LISTA 2 -->
            <div class="container-lista">
                <ul>
                    <li>
                        <h2>DC COMICS</h2>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                     <li>
                        <a href="#">Characters</a>
                    </li>

                     <li>
                        <a href="#">Characters</a>
                    </li>

                     <li>
                        <a href="#">Characters</a>
                    </li>

                     <li>
                        <a href="#">Characters</a>
                    </li>

                    
                </ul>
            </div>

    <!-- CONTAINER LISTA 3 -->
            <div class="container-lista">
                <ul>
                    <li>
                        <h2>DC COMICS</h2>
                    </li>
                    
                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>

                    <li>
                        <a href="#">Characters</a>
                    </li>
                </ul>
            </div>
            


        </section>

    <!-- Contenitore sezione registrazione e Social Media -->
        <section class="sign-up-container">

    <!-- Sezione bottone registrazione -->
            <div>
                <input type="button" value="SIGN-UP NOW!" class="button-sign-up" onclick="msg()"> 
            </div>

            <div class="container-social-media">
    <!-- Sezione Social Media -->
                <h2>FOLLOW US</h2>
                <img src="../assets/vue-dc-comics-1/img/footer-facebook.png" alt="Facebook">
                <img src="../assets/vue-dc-comics-1/img/footer-twitter.png" alt="Twitter">
                <img src="../assets/vue-dc-comics-1/img/footer-youtube.png" alt="Youtube">
                <img src="../assets/vue-dc-comics-1/img/footer-pinterest.png" alt="Pinterest">
                <img src="../assets/vue-dc-comics-1/img/footer-periscope.png" alt="Maps">
            </div>

        </section>

    </footer>
</template>

<script>
export default {
    name: "Footer",
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.jumbotron{
    display: flex;
    padding-top: 20px;
    padding-bottom: 20px;
    background-image: url("../assets/vue-dc-comics-1/img/footer-bg.jpg");
    background-size: cover;
    color: $thirdColor;
}

.container-lista{
    margin-left: 30px;
}

ul{
    list-style: none;
}

li a{
    color: $thirdColor;
    padding: 20px;
    text-decoration: none;
    font-weight: 300;
}

li h2{
    font-weight: 600;
}

.sign-up-container{
    background-color: $fourthColor;
    padding: 30px;
    display: flex;
    justify-content: space-between;
}

.button-sign-up{
    padding: 20px;
    border: 2.5px solid $primaryColor;
    background-color: $fourthColor;
    color: $thirdColor;
    font-weight: 600;
    font-size: 1.2em;
}

.container-social-media{
    display: flex;
    align-items: center;
}

.container-social-media h2{
    color: $primaryColor;
    padding-right: 20px;
    font-weight: 600;
}

.container-social-media img{
    height: 40px;
    padding: 10px;
}




</style>