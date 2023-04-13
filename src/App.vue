<script>
import AppHeader from './components/AppHeader.vue'
import AppContent from './components/AppContent.vue'

export default {

  name: 'App',

  components: {
    AppHeader,
    AppContent

  }

}

</script>

<template>
  <AppHeader></AppHeader>

  <main>
    <AppContent></AppContent>

    <div class="container">
      <div class="row">
        <div class="col"></div>
      </div>
    </div>

  </main>
  <footer></footer>
</template>

<style scoped lang="scss"></style>
