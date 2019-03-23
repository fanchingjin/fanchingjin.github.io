<template lang="pug">
  #app
    HomeCover/
    BaseReport/
</template>

<script>
import HomeCover from './components/HomeCover.vue';
import BaseReport from './components/BaseReport.vue';

export default {
  name: 'app',
  components: {
    HomeCover,
    BaseReport,
  },
};
</script>

<style lang="scss">
body {
  background-color: #f6f6f6;
}
.full-page {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.cover-img {
  background-position: top center;
  background-size: cover;
  background-repeat: no-repeat;
}
.fade-in {
  opacity: 1;
}
</style>
