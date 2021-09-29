
<template>
    <div class="film-element">
        <img :src="src" alt="immagine serie">
        <h3>{{ title }}</h3>
    </div>
</template>


<script>
export default {
    name: 'FilmObject',
    props: ["title", "src"],
}
</script>

<style scoped>

.film-element{
    flex-basis: calc(100% / 6 - 45px);
    margin: 20px;
}

img{
    width: 100%;
    
}

h3{
    text-align: center;
    font-size: 1em;
}

</style>