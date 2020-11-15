<template lang="pug">
  .video-window
    p Video Area
</template>

<style lang="scss" scoped>
  .video-window {
    height: 30%;
  }
</style>

<script lang="ts">
  import { Component, Vue } from 'nuxt-property-decorator';
  @Component
  export default class Video extends Vue {}
</script>
