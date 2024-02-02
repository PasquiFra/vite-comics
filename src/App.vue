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

<style lang="scss">
@use '@/assets/scss/style.scss';
</style>
