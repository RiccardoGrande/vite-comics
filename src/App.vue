<script>
import AppHeader from './components/AppHeader.vue'
import AppContent from './components/AppContent.vue'
import AppLinks from './components/AppLinks.vue'
import AppInfo from './components/AppInfo.vue'
import AppFooter from './components/AppFooter.vue'

export default {

  name: 'App',

  components: {
    AppHeader,
    AppContent,
    AppLinks,
    AppInfo,
    AppFooter
  }

}

</script>

<template>
  <AppHeader></AppHeader>

  <main>
    <AppContent></AppContent>

    <AppLinks></AppLinks>

    <AppInfo></AppInfo>


  </main>
  <footer>
    <AppFooter></AppFooter>
  </footer>
</template>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>
