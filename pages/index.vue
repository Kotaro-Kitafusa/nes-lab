<template lang="pug">
  .index-container
    Video
    .nes-container.with-title.is-centered
      p こんにちは! SNESの雰囲気が味わえるSNES-Labです
      .test aiueo
        .nes-text.is-primary yoyo
      .test2 hi
</template>

<script lang="ts">
import Vue from 'vue'
import Video from '~/pages/video.vue'
export default {
  components: {
    Video
  }
}

</script>

<style lang="scss" scoped>
  .index-container {
    display: flex;
    flex-direction: column;
    height: 80%;

    .nes-container {
      margin-top: 1rem;
    }
  }
</style>
