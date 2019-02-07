<template lang="pug">
  #app
    phone-ixlayer
</template>

<script>
import PhoneIxlayer from "@/components/Phone-ixlayer";
export default {
  name: "app",
  components: {
    PhoneIxlayer
  }
};
</script>

<style lang="scss">
//colors
$blue: #63c6fe;

body {
  margin: 0;
}

#app {
  background: $blue;
  overflow-x: hidden;
  height: 100vh;
}

.d-flex {
  height: 100%;
  width: 100%;
  display: flex;
}

.justify-center {
  justify-content: center;
}
</style>
