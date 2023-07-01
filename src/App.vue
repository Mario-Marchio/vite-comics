<script>
import appHeader from "./components/AppHeader.vue"
import appMain from "./components/AppMain.vue"
import appFooter from "./components/AppFooter.vue"
export default {
  data() {
    return {

    }
  },
  components: {
    appHeader: appHeader,
    appMain: appMain,
    appFooter: appFooter,

  }
}
</script>
<template>
  <appHeader />
  <appMain />
  <appFooter />
</template>
<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  height: auto;
  max-width: 100%;
}

li {
  list-style-type: none;
  align-items: center;
  display: flex;
}

.d-flex {
  display: flex;
}

a {
  text-decoration: none;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
}

.h-40 {
  height: 40px;
}

.bgc-black {
  background-color: black;
}

.bgc-l-blue {
  background-color: #0282F9;
}

.color-black {
  color: black;
}
</style>