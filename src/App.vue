<template>
  <div id="app">
    <router-link to="/goods">商品</router-link>
    <router-link to="/login">测试</router-link>
    <!-- <goods></goods> -->
    <router-view></router-view>
  </div>
</template>
<script>
// import goods from './components/Goods'
export default {
  data () {
    return {
      playConfig: {}
    }
  },
  ready () {
  },
  methods: {
  },
  components: {
    // 'goods': goods
  }
}
</script>

<style>
@import './assets/css/base.css';
</style>
