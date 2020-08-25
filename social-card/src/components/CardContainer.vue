<!--Markup/HTML-->
<template>
  <div class="container">
    <CardBanner />
    <CardContent />
  </div>
</template>

<!--Javascript-->
<script>
import CardBanner from "./CardBanner.vue";
import CardContent from "./CardContent.vue";

export default {
  components: {
    CardBanner,
    CardContent,
  },
};
</script>

<!--CSS-->
<style scoped>
</style>