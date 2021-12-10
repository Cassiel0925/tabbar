<template>
  <div id="app">
    <router-view></router-view>
    <!-- 3. 使用 -->
    <tab-bar>
      <tab-bar-item path="/home">
        <i class="icon-home" slot="item-icon"></i>
        <i class="icon-home" slot="item-icon-active" style="color: pink"></i>
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category">
        <i class="icon-grid" slot="item-icon"></i>
        <i class="icon-grid" slot="item-icon-active" style="color: pink"></i>
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart">
        <i class="icon-cart" slot="item-icon"></i>
        <i class="icon-cart" slot="item-icon-active" style="color: pink"></i>
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile">
        <i class="icon-user" slot="item-icon"></i>
        <i class="icon-user" slot="item-icon-active" style="color: pink"></i>
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
// 1. 导入组件
import TabBar from './components/tabbar/TabBar.vue'
import TabBarItem from './components/tabbar/TabBarItem.vue'

export default {
  name: 'App',
  // 2. 注册组件
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style>
  @import "./assets/css/base.css";
  @import "./assets/css/style.css"
  
</style>
