<template>
  <div id="app">
    <router-view></router-view>
    <!-- 3. 使用 -->
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import MainTabBar from './components/mainTabBar/MainTabBar.vue'

export default {
  name: 'App',
  components: {
    MainTabBar
  }
  
}
</script>

<style>
  @import "./assets/css/base.css";
  @import "./assets/css/style.css"
  
</style>
