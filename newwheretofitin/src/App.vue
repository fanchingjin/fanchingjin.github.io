<template>
  <div id="app">
    <HomeCover/>
    <BasePage/>
  </div>
</template>

<script>
import HomeCover from './components/HomeCover.vue';
import BasePage from './components/BasePage.vue';

export default {
  name: 'app',
  components: {
    HomeCover,
    BasePage,
  },
};
</script>

<style lang="scss">
.fade-in {
  opacity: 1;
}
</style>
