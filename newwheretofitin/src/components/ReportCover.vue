<template lang="pug">
  section.full-page
    .report-cover.full-page#report1
    .report-cover.cover-img.full-page#report2
    .report-cover.cover-img.full-page#report3
      BaseReport/
    .report-cover.cover-img.full-page#report4
    .report-cover.cover-img.full-page#report5
</template>

<script>
import BaseReport from './BaseReport.vue';

export default {
  name: 'ReportCover',
  components: {
    BaseReport,
  },
};
</script>

<style lang="scss">
// .report {
//   overflow: hidden;
// }
.report-cover {
  transform: translateY(-100vh);
  z-index: 19;
  display: flex;
  align-items: center;
}
#report1 {
  background-image: url(../assets/Cover/report1_bottom--lap.png), url(../assets/Cover/report1_top--lap.jpg);
  background-position: center bottom, center top;
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed, scroll;
}
#report2 {
  background-image: url(../assets/Cover/report2--lap.jpg);
}
#report3 {
  background-image: url(../assets/Cover/report3--lap.jpg);
}
#report4 {
  background-image: url(../assets/Cover/report4--lap.jpg);
}
#report5 {
  background-image: url(../assets/Cover/report5--lap.jpg);
}
</style>
