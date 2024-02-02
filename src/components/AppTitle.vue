<script>
export default {
    name: "AppTitle",
    data: () => ({
        exMessage: "La mia prima app con Vite!"
    })

}
</script>

<template>
    <h1>{{ exMessage }}</h1>
</template>

<style>
h1 {
    text-align: center;
}
</style>