<template>
  <div id="app">
    <TheHeader></TheHeader>
    <TheMain></TheMain>
    <TopFooter></TopFooter>
    <BottomFooter></BottomFooter>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';
import TopFooter from './components/TopFooter.vue';
import BottomFooter from './components/BottomFooter.vue';

export default {
  name: 'App',
  components: {
    TheHeader,
    TheMain,
    TopFooter,
    BottomFooter
  },
  data() {

  }
}
</script>

<style lang="scss">
</style>
