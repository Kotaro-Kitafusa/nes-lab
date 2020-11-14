<template lang="pug">
  div
    header
      .title
        h1 NES-lab
      .menu
        ul
         li
          a(href="#") about
         li
          a(href="#") chat

    nuxt.content-area

    footer
      h1 Video Title

</template>

<style lang="scss" scoped>
  @import '../assets/css/header_footer';
</style>

<script lang="ts">
  import { Component, Vue } from 'nuxt-property-decorator';
  @Component
  export default class DefaultLayout extends Vue {}
</script>
