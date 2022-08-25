<template>
  <div id="app">
    <TheHeader :home="home" :about="about" :prices="prices" :courses="courses" :locations="locations" :blog="blog">
    </TheHeader>
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
    return {
      home: 'HOME',
      about: 'ABOUT',
      prices: 'PRICES',
      courses: 'COURSES',
      locations: 'LOCATIONS',
      blog: 'BLOG',
    }
  }
}
</script>

<style lang="scss">
</style>
