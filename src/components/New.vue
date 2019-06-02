<template>
  <div class="not-main">
    this is the new component
  </div>
</template>

<script>
  export default {
    data() {
      return {
        color: 'red'
      }
    }
    
  }
</script>

<style lang="sass" scoped>
  @import '../Sass/app'
  .not-main
    color: $black
    font-family: monospace
</style>