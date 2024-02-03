<script>
import AppTitle from "./components/AppTitle.vue"
import AppHero from "./components/AppHero.vue"

export default {
  name: "Hello-Vite!",
  components: {
    AppHero,
    AppTitle,
  }
}

</script>

<template>
  <header>
    <AppTitle />
    <AppHero />
  </header>
</template>

<style scoped>
header {
  margin: 0;
}
</style>
