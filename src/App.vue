<template>

  <div id="app">

    <header-content />
    <jumbo-content />
    <info-content />
    <footer-nav />
    <footer-contacts />

  </div>

</template>

<script>

  import HeaderContent from './components/HeaderContent.vue';
  import JumboContent from './components/JumboContent.vue';
  import InfoContent from './components/InfoContent.vue';
  import FooterNav from './components/FooterNav.vue';
  import FooterContacts from './components/FooterContacts.vue'

  export default {
    name: 'App',
    components: {
      HeaderContent,
      JumboContent,
      InfoContent,
      FooterNav,
      FooterContacts
    }
  }

</script>

<style lang="scss">

  @import '@/style/main.scss';

</style>
