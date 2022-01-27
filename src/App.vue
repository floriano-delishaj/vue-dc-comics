<template>

  <div id="app">

    <header-content />

  </div>

</template>

<script>

  import HeaderContent from './components/HeaderContent.vue'

  export default {
    name: 'App',
    components: {
      HeaderContent,
    }
  }

</script>

<style lang="scss">

  @import '@/style/main.scss';

</style>
