<template>
  <div>
    <TitleComp />
    <JumbotronComp />
  </div>
</template>

<script>
import TitleComp from "./components/TitleComp.vue";
import JumbotronComp from "./components/JumbotronComp.vue";


export default {
  name: 'App',
  components: {
    TitleComp,
    JumbotronComp,
    
}
}
</script>

<style lang="scss">

</style>
