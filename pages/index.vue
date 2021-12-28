<template>
  <Header />
</template>

<script lang="ts">
import Vue from 'vue'
import Header from '@/components/Header/Header.vue';

export default Vue.extend({
  name: 'IndexPage',
  components: {
    Header
  }
})
</script>

<style lang="scss" scoped>
  @import '@/assets/styles/main.scss';
  
</style>
