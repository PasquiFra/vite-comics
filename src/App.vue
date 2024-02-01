<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue"
import AppFooterTop from "./components/AppFooterTop.vue"
import AppFooterBottom from "./components/AppFooterBottom.vue"

export default {
  name: "Vite-comics",
  components: {
    AppHeader, AppMain, AppFooterTop, AppFooterBottom
  },
  data: () => ({
    data: [
      {
        text: 'Characters',
        url: '#',
        current: false,
      },
      {
        text: 'Comics',
        url: '#',
        current: true,
      },
      {
        text: 'Movies',
        url: '#',
        current: false,
      },
      {
        text: 'TV',
        url: '#',
        current: false,
      },
      {
        text: 'Games',
        url: '#',
        current: false,
      },
      {
        text: 'Collectibles',
        url: '#',
        current: false,
      },
      {
        text: 'Videos',
        url: '#',
        current: false,
      },
      {
        text: 'Fans',
        url: '#',
        current: false,
      },
      {
        text: 'News',
        url: '#',
        current: false,
      },
      {
        text: 'Shop',
        url: '#',
        current: false,
      },
    ]
  })
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooterTop />
  <AppFooterBottom />
</template>

<style></style>
