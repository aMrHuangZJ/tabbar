<template>
    <!-- <tab-bar>底部导航组件 -->
    <tab-bar>
      <!-- <tab-bar-item>底部导航组件的小组件 -->
      <tab-bar-item path="/home" activeColor="blue">
          <img slot="item-icon" src="../assets/img/Tabbar/tab2.png">
          <img slot="item-icon-active" src="../assets/img/Tabbar/tab6.png">
          <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="blue">
          <img slot="item-icon" src="../assets/img/Tabbar/tab1.png">
          <img slot="item-icon-active" src="../assets/img/Tabbar/tab5.png">
          <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="blue">
          <img slot="item-icon" src="../assets/img/Tabbar/tab9.png">
          <img slot="item-icon-active" src="../assets/img/Tabbar/tab10.png">
          <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="blue">
          <img slot="item-icon" src="../assets/img/Tabbar/tab3.png">
          <img slot="item-icon-active" src="../assets/img/Tabbar/tab7.png">
          <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>

<script>
 import TabBar from './tabbar/Tabbar'
  import TabBarItem from './tabbar/TabBarItem'
export default {
    name: 'MainTabBar',
    components: {
        TabBar,
        TabBarItem
    }
}
</script>

<style scoped>

</style>