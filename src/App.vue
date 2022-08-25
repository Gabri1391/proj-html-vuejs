<template>
  <div>
    <BaseHeader/>
    <TheMain/>
    <BaseFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import TheMain from './components/TheMain.vue';
import BaseFooter from './components/BaseFooter.vue';


export default {
  name: 'App',
  components: {
    BaseHeader,
    TheMain,
    BaseFooter
  }

}
</script>

<style lang="scss">
@import './assets/sass/style.scss';
@import'./assets/sass/_vars.scss';
</style>
