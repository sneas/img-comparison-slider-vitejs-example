<template>
  <ImgComparisonSlider>
    <img
        slot="first"
        style="width: 100%"
        src="https://sneas.github.io/img-comparison-slider/demo/images/before.webp"
    />
    <img
        slot="second"
        style="width: 100%"
        src="https://sneas.github.io/img-comparison-slider/demo/images/after.webp"
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
  },
  methods: {
    onSlide: (event: any) => {
      console.log(event);
    }
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
