<template lang="pug">
  #app
    HomeCover/
    ReportCover/
</template>

<script>
import HomeCover from './components/HomeCover.vue';
import ReportCover from './components/ReportCover.vue';

export default {
  name: 'app',
  components: {
    HomeCover,
    ReportCover,
  },
};
</script>

<style lang="scss">
html {
  font-size: 10px;
}
body {
  background-color: #d5e6f0;
  font-family: "Noto Sans CJK TC", sans-serif;
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
button {
  border: 0;
  outline: 0;
  cursor: pointer;
  font-family: "Noto Sans CJK TC", sans-serif;
}
</style>
