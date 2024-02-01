<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue"
import AppFooterTop from "./components/AppFooterTop.vue"
import AppFooterCenter from "./components/AppFooterCenter.vue"
import AppFooterBottom from "./components/AppFooterBottom.vue"

export default {
  name: "Vite-comics",
  components: {
    AppHeader, AppMain, AppFooterTop, AppFooterCenter, AppFooterBottom
  },
  data: () => ({

  })
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooterTop />
  <AppFooterCenter />
  <AppFooterBottom />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500;600;700;800&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Open Sans', "Open Sans Condensed";
}

.container {
  width: 1200px;
  margin: 0 auto;
  border: 1px solid black;
}

.flex {
  display: flex;
  flex-grow: 0;
  flex-shrink: 0;
}

.center {
  text-align: center;
  justify-content: center;
  align-items: center;
}

.list-setup {
  list-style-type: none;
}
</style>
