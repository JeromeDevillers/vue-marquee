<script>
import Vue from 'vue';
import VueMarquee from '@/vue-marquee.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueMarquee
  }
});
</script>

<template>
  <div id="app">
    <vue-marquee />
  </div>
</template>
