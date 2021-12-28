<template>
  <header class="header">
    <header-logo />
    <header-navbar />
  </header>
</template>

<script lang="ts">
import Vue from 'vue'
import HeaderLogo from '@/components/Header/HeaderLogo/HeaderLogo.vue';
import HeaderNavbar from '@/components/Header/HeaderNavbar/HeaderNavbar.vue';

export default Vue.extend({
  components: {
    HeaderLogo,
    HeaderNavbar
  }
})
</script>

<style lang="scss" scoped>
  .header {
    width: 100vw;

  }
</style>