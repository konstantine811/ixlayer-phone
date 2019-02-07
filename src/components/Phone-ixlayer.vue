<template lang="pug">
  .d-flex.justify-center.svg__wrap
    .svg
      include ../assets/svg/phone-ixlayer.svg
</template>

<script>
export default {
  name: "PhoneIxlayer",
  data() {
    return {
      animated: false
    };
  },
  methods: {
    ixlayerClick() {
      this.animated = !this.animated;
    }
  }
};
</script>

<style scoped lang="scss">
@import "@/assets/styles/svg.scss";
.svg__wrap {
  padding-top: 6%;
}

.svg {
  width: 54%;
  height: auto;
}
</style>
