<template>
    <AppTitle />
    <AppHero />
</template>

<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

  export default {
    name:'App',
    components:{
      AppTitle,
      AppHero
    },data(){

    },

  }
</script>

<style scoped>

</style>