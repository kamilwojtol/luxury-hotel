<template>
  <div class="logo">
    <div class="logo-text">
      <span class="logo-text-big">{{ bigText }}</span>
      <span class="logo-text-small">{{ smallText }}</span>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  props: {
    bigText: {
      type: String,
      default: 'Luxury'
    },
    smallText: {
      type: String,
      default: 'Hotels'
    },
  }
})
</script>

<style lang="scss" scoped>
  .logo {
    background-color: $color-gold;
    padding: 40px 20px 20px 20px;
    width: 250px;
    border-radius: 0 0 20px 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

    .logo-text {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;

       .logo-text-big,
    .logo-text-small {
      display: block;
      font-family: $font-secondary;
      font-weight: 700;
      text-transform: uppercase;
      color: $color-darkblue;
    }

    .logo-text-big {
      font-size: 40px;
      letter-spacing: 5px;
      }

    .logo-text-small {
      font-size: 15px;
      letter-spacing: 10px;
      }
    }
  }
</style>