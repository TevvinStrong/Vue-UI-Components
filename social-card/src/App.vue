<template>
  <div id="app">
    <HeaderContainer />
  </div>
</template>

<script>
import HeaderContainer from "./components/HeaderContainer.vue";
export default {
  name: "App",
  components: {
    HeaderContainer,
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

html,
a {
  font-size: 62.5%;
  color: #236cfe;
}

span {
  color: #768592;
}
</style>
