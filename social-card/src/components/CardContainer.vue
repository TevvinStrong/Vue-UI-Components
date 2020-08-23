<!--Markup/HTML-->
<template>
  <div class="container">
    <CardBanner />
    <CardIcons />
  </div>
</template>

<!--Javascript-->
<script>
import CardBanner from "./CardBanner.vue";
import CardIcons from "./CardIcons.vue";

export default {
  components: {
    CardBanner,
    CardIcons,
  },
};
</script>

<!--CSS-->
<style scoped>
</style>