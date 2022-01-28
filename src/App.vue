<template>

  <div id="app">

    <header-content :nav="nav"/>
    <jumbo-content />
    <main-cards />
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
  import FooterContacts from './components/FooterContacts.vue';
  import MainCards from './components/MainCards.vue';
  import "bootstrap/dist/css/bootstrap.min.css";
  import "bootstrap";

  export default {
    name: 'App',
    components: {
      HeaderContent,
      JumboContent,
      InfoContent,
      FooterNav,
      FooterContacts,
      MainCards
    },
     data() {
        return {
            nav: [
                {
                id: "CtuVioLAXk",
                label: "characters",
                url: "/",
                },
                {
                id: "cRSoVCHuYo",
                label: "comics",
                url: "/",
                },
                {
                id: "NHkzXgz1i9",
                label: "movies",
                url: "/",
                },
                {
                id: "yHqHSCrLA2",
                label: "tv",
                url: "/",
                },
                {
                id: "cGccpQ4CL8",
                label: "games",
                url: "/",
                },
                {
                id: "MDzDAAzGyB",
                label: "collectibles",
                url: "/",
                },
                {
                id: "iZfvIg40A3",
                label: "videos",
                url: "/",
                },
                {
                id: "r48PJscQYk",
                label: "fans",
                url: "/",
                },
                {
                id: "So8IvoYhxw",
                label: "news",
                url: "/",
                },
                {
                id: "qyAhVJKwHA",
                label: "shop",
                url: "/",
                },
            ],
        };
    },
  }

</script>

<style lang="scss">

  @import '@/style/main.scss';

</style>
