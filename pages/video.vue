<template lang="pug">
  video.video-window(src="../assets/videos/zelda.mp4" autoplay loop playline muted)
</template>

<style lang="scss" scoped>
  .video-window {
    height: 50%;
    width: 100%;
  }
</style>

<script lang="ts">
  import { Component, Vue } from 'nuxt-property-decorator';
  @Component
  export default class Video extends Vue {}
</script>
