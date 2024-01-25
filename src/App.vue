<script>
import AppHeader from './components/AppHeader.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
  },
  methods: {
  }
}

</script>

<template>
  <AppHeader></AppHeader>

  <footer>

  </footer>
</template>

<style lang="scss">
@use '../src/assets/scss/partials/variables' as *;



.card {
  background: $yugioh__bg;
}
</style>