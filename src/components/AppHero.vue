<script>
export default {
    name: "AppHero",
    data: () => ({
        image_name: "milano_skyline"
    }),
    methods: {
        createImagePath(image_name) {
            const url = new URL(`../assets/${image_name}.jpg`, import.meta.url);
            return url.href
        }
    }

}
</script>

<template>
    <figure>
        <img :src="createImagePath(image_name)" :alt="image_name">
    </figure>
</template>

<style>
figure {
    margin: 0;
    text-align: center;
    background-color: blanchedalmond;
}
</style>