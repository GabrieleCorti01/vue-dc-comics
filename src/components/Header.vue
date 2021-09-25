<template>
    <header class="container-header">
    <!-- Logo immagine -->
        <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="">
    <!-- Navbar -->
        <nav>
            <ul>
                <li>
                    <a href="#">CHARACTERS</a>
                </li>

                 <li>
                    <a href="#">COMICS</a>
                </li>

                 <li>
                    <a href="#">MOVIES</a>
                </li>

                 <li>
                    <a href="#">TV</a>
                </li>

                 <li>
                    <a href="#">GAMES</a>
                </li>

                 <li>
                    <a href="#">COLLECTIBLES</a>
                </li>

                 <li>
                    <a href="#">VIDEOS</a>
                </li>

                 <li>
                    <a href="#">FANS</a>
                </li>

                 <li>
                    <a href="#">NEWS</a>
                </li>

                 <li>
                    <a href="#">SHOP</a>
                </li>
            </ul>

        </nav>




    </header>
</template>

<script>
export default {
    name: "Header",
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

header{
    font-family: $mainFont;
}

.container-header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
}

ul{
    display: flex;
    list-style: none;
}

li a{
    color: $secondaryColor;
    padding: 20px;
    text-decoration: none;
    font-weight: 600;
}


</style>