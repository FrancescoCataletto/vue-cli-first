<template>
  <div id="app">
    <TitleElement />

    <HeroElement />
  </div>
</template>

<script>
import TitleElement from "./components/TitleElement.vue"
import HeroElement from "./components/HeroElement.vue"

export default {
  name: 'App',
  components: {
    TitleElement,
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
