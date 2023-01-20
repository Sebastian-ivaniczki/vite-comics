<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
export default {
  data(){
    return {

    }
  },
  components: { AppHeader, AppMain, AppFooter },
}
</script>

<template>
  <header>
    <app-header></app-header>
  </header>
  <main>
    <app-main></app-main>
  </main>
  <footer>
    <app-footer></app-footer>
  </footer>
</template>

<style>
</style>
