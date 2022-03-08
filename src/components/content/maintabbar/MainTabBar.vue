<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="deepPink">
    <img slot="item-icon" src="../../../assets/img/tabbar/home.svg" alt="">
    <img slot="item-icon-active" src="../../../assets/img/tabbar/home-active.svg" alt="">
    <div slot="item-text">首页</div>
    </tab-bar-item>
	
    <tab-bar-item path="/category" activeColor="deepPink">
    <img slot="item-icon" src="../../../assets/img/tabbar/fle.svg" alt="">
    <img slot="item-icon-active" src="../../../assets/img/tabbar/fle-actieve.svg" alt="">
    <div slot="item-text">分类</div>
    </tab-bar-item>
	
    <tab-bar-item path="/cart" activeColor="deepPink">
    <img slot="item-icon" src="../../../assets/img/tabbar/cart.svg" alt="">
    <img slot="item-icon-active" src="../../../assets/img/tabbar/cart-active.svg" alt="">
    <div slot="item-text">购物车</div>
    </tab-bar-item>
	
    <tab-bar-item path="/profile" activeColor="deepPink">
    <img slot="item-icon" src="../../../assets/img/tabbar/me.svg" alt="">
    <img slot="item-icon-active" src="../../../assets/img/tabbar/me-active.svg" alt="">
    <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from '../../common/tabbar/TabBar.vue'
  import TabBarItem from'../../common/tabbar/TabBarItem.vue'

  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>
</style>
