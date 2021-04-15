<template lang="html">
  <div class="container">
    <header-banner/>
    <video-instruction/>
    <result-month/>
  </div>
</template>

<script>

import HeaderBanner from '../components/header-banner.vue';
import VideoInstruction from '../components/video-instruction.vue';
import ResultMonth from '../components/result-month.vue';

export default {
  name: 'Home',
  components: { ResultMonth, VideoInstruction, HeaderBanner },
};
</script>
