
<template>
    <div class="film-element">
        <h3>{{ title }}</h3>
    </div>
</template>


<script>
export default {
    name: 'FilmObject',
    props: ["title"],
}
</script>

<style scoped>

.film-element{
    border: 2px solid white;
    height: 200px;
    width: 200px;
}

</style>