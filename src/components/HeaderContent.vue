<template>
  <header>
    <div class="container">
      <div class="header-left">
        <img src="@/assets/dc-logo.png" />
      </div>

      <div class="header-right">
        <ul>
          <li v-for="button in nav" :key="button.id">
            <a :href="button.url">
              {{ button.label }}
            </a>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
    export default {
      props: {
        nav: Array,
      }
    };
</script>

<style lang="scss" scoped>

  @import "@/style/headerContent.scss";

</style>