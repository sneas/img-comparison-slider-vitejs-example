<template>
  <ImgComparisonSlider>
    <img
        slot="first"
        style="width: 100%"
        src="https://img-comparison-slider.sneas.io/demo/images/before.webp"
    />
    <img
        slot="second"
        style="width: 100%"
        src="https://img-comparison-slider.sneas.io/demo/images/after.webp"
    />
  </ImgComparisonSlider>
</template>

<script>
import { ImgComparisonSlider } from '@img-comparison-slider/vue';

export default {
  name: 'ExampleComponent',
  components: {
    ImgComparisonSlider,
  },
};
</script>
