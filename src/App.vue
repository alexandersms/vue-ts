<template>
  <div id="app">
    <app-navbar-vue></app-navbar-vue>
    <router-view></router-view>
    <app-footer-vue></app-footer-vue>
  </div>
</template>

<script>
import { Vue, Component } from 'vue-property-decorator';
import AppFooterVue from './components/AppFooter.vue';
import AppNavbarVue from './components/AppNavbar.vue';

@Component({
  components: {
    AppFooterVue,
    AppNavbarVue,
  },
})
export default class App extends Vue {}
</script>

<style></style>
