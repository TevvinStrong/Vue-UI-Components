<!--Markup/HTML-->
<template>
  <div class="container">
    <Thumbnail />
    <HeaderTitle />
    <HeaderContent />
  </div>
</template>




<!--Javascript-->
<script>
import Thumbnail from "./ImageThumbnail.vue";
import HeaderTitle from "./HeaderTitle.vue";
import HeaderContent from "./HeaderContent.vue";
export default {
  components: {
    Thumbnail,
    HeaderTitle,
    HeaderContent,
  },
};
</script>




<!--CSS-->
<style Scoped>
.container {
  display: flex;
  flex-wrap: no-wrap;
  flex-direction: row;
  justify-content: flex-start;
}
</style>