<template>
    
    <AppHeader />
    <AppHero />
    <AppMain />
    <AppFooter />

</template>

<script>
  import AppHeader from './components/AppHeader.vue';
  import AppHero from './components/AppHero.vue';
  import AppMain from './components/AppMain.vue';
  import AppFooter from './components/AppFooter.vue';

  export default {
    name: "App",
    components: {
      AppHeader,
      AppHero,
      AppMain,
      AppFooter,
    },
  }
</script>

<style lang="scss">

</style>