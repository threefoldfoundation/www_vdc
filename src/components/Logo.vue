<template>
  <div>
    <img v-if="dark" src="../assets/vdc_white.png" alt="" />
    <img v-else src="../assets/VDC_logo2.png" alt="" />
  </div>
</template>

<script>
export default {
  props: {
    width: {
      type: Number,
      default: 40,
    },
    dark: {
      type: Boolean,
      default: false,
    },
  },
  computed: {
    getWidth() {
      return this.width;
    },

    getHeight() {
      return Math.ceil((this.getWidth / 48) * 48);
    },
  },
};
</script>

