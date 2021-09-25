
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
    </footer>
</template>

<script>
export default {
    name: "Footer",
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

footer{
    background-image: src("../assets/vue-dc-comics-1/img/footer-bg.png");
}

.jumbotron{
    display: flex;
    padding-top: 20px;
}

.container-lista{
    margin-left: 30px;
}

ul{
    list-style: none;
}

li a{
    color: $secondaryColor;
    padding: 20px;
    text-decoration: none;
}





</style>