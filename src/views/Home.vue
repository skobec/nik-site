<template lang="html">
  <div>
    <header-banner/>
    <div class="container">
      <video-instruction/>
      <result-month/>
      <lessons-block/>
      <app-download-block/>
    </div>
    <footer-landing/>
  </div>
</template>

<script>

import HeaderBanner from '../components/header-banner.vue';
import VideoInstruction from '../components/video-instruction.vue';
import ResultMonth from '../components/result-month.vue';
import LessonsBlock from '../components/lessons-block.vue';
import AppDownloadBlock from '../components/app-download-block.vue';
import FooterLanding from '../components/footer.vue';

export default {
  name: 'Home',
  components: {
    FooterLanding,
    AppDownloadBlock,
    LessonsBlock,
    ResultMonth,
    VideoInstruction,
    HeaderBanner,
  },
};
</script>
