<template>
  <div id="app">
    <HeaderContainer />
    <CardContainer />
  </div>
</template>

<script>
import HeaderContainer from "./components/HeaderContainer.vue";
import CardContainer from "./components/CardContainer.vue";

export default {
  name: "App",
  components: {
    HeaderContainer,
    CardContainer,
  },
};
</script>

<style>
/* 
CSS Reset
*/

* {
  margin: 0;
  padding: 0;
  font-size: 1em;
  font-family: inherit;
  background-color: #15202b;
  color: #ffffff;
}

html {
  font-size: 62.5%;
  color: #495161;
  width: 800px;
  max-width: 100%;
  margin: 0 auto;
}

a {
  font-size: 13px;
  text-decoration: none;
  color: #1b95e0;
  font-weight: 500;
}

span {
  color: #768592;
}
</style>
