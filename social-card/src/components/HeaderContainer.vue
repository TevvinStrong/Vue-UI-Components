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
export default {
  components: {
    Thumbnail,
    HeaderTitle,
  },
};
</script>




<!--CSS-->
<style Scoped>
.container {
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: flex-start;
  width: 800px;
  max-width: 100%;
}
</style>