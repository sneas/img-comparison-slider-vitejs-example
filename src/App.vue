<template>
  <ImgComparisonSlider>
    <img
        slot="before"
        style="width: 100%"
        src="https://sneas.github.io/img-comparison-slider/demo/images/cat.jpg"
    />
    <img
        slot="after"
        style="width: 100%"
        src="https://sneas.github.io/img-comparison-slider/demo/images/dog.jpg"
    />
  </ImgComparisonSlider>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { ImgComparisonSlider } from '@img-comparison-slider/vue'

export default defineComponent({
  name: 'App',
  components: {
    ImgComparisonSlider
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
