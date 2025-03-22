<template>
  <MainNavbar/>
  <MainHeader/>
  <LatestWork/>
</template>

<script>
import LatestWork from './components/LatestWork.vue';
import MainHeader from './components/MainHeader.vue';
import MainNavbar from './components/MainNavbar.vue';

export default {
  name: 'App',
  components: {
    MainNavbar,
    MainHeader,
    LatestWork,
  }
}
</script>

<!-- <style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style> -->
