<!--Markup/HTML-->
<template>
  <div class="header_title">
    <h5>
      Porsche Motorsport
      <fa-icon class="icon" icon="check-circle" />
      <span>@PorscheRaces - Aug 14</span>
    </h5>
    <HeaderContent />
  </div>
</template>




<!--Javascript-->
<script>
import HeaderContent from "./HeaderContent.vue";

export default {
  components: {
    HeaderContent,
  },
};
</script>




<!--CSS-->
<style Scoped>
.header_title {
  padding-top: 5px;
}

h5 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 13px;
  margin-top: 46px;
  margin-bottom: 5px;
  margin-left: 13px;
}

span {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 12px;
  font-weight: 500;
  margin-top: 48px;
  margin-left: 1%;
}
</style>