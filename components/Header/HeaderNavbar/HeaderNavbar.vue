<template>
  <nav>
    <p>{{ text }}</p>
  </nav>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      text: `Hi, I'm navbar`
    }
  }
})
</script>