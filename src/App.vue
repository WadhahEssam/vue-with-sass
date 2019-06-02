<template>
  <div>
    <div class="main">
      hello there
    </div>
    <New/>
  </div>
</template>

<script>
  import New from './components/New'

  export default {
    name: 'app',
    components: {
      New
    }
  }
</script>

<style lang="sass" scoped>
  $font: monospace

  .main
    background: red
    height: 200px
    margin: 20px
    padding: 20px
    font-family: $font
</style>