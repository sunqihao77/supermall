<template>
  <div id="app">
    <router-view></router-view>
    <tabmain></tabmain>
  </div>
</template>

<script>
import tabmain from './components/content/mainTabbar/MainTabBar.vue'

export default {
  name: 'App',
  components: {
    tabmain
  }
}
</script>

<style>
	/* @import url("./assets/css/base.css"); */
	/* @import url("src/assets/css/base"); */
	@import url("assets/css/base.css");
</style>
