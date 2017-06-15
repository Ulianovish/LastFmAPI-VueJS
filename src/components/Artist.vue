<template>
    <li>
        <h2>
            <a :href="artist.url" target="_blank">{{ artist.name }}</a>           
        </h2>
        <img :src="artist.image[2]['#text']">
    </li>
</template>

<script>
export default {
    name: 'artist',
    props: [ 'artist' ]
}
</script>

<style scoped>
li {
    display: inline-block;
    margin: 10px;
    background: darkslategrey;
    padding: 10px;
    border: 3px solid darkseagreen;
    border-radius: 10px;
}
</style>
