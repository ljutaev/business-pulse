<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  mounted() {
    document.body.classList.add("loaded");
  },
  destroyed() {
    document.body.classList.remove("loaded");
  },
};
</script>

<style lang="scss">

</style>
