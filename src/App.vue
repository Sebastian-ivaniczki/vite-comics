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
/* reset */
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: sans-serif;
}

/* generics */
.container{
  width: 1200px;
  margin: 0 auto;
}
img{
max-width: 100%;
height: auto;
}

a {
  color: #000;
  text-decoration: none;
}
</style>
