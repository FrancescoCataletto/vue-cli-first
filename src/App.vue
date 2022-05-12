<template>
  <div id="app">
    <titleElement />

    <HeroElement />
  </div>
</template>

<script>
import titleElement from "./components/titleElement.vue"
import HeroElement from "./components/HeroElement.vue"

export default {
  name: 'App',
  components: {
    titleElement,
    HeroElement
}
}
</script>

<style>
  #app{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
</style>
