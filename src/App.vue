<template>
  <div id="app">
    <!-- <div class="header">I am header;</div> -->
    <v-header></v-header>
    <div class="tab">
      <div class="item">商品</div>
      <div class="item">评价</div>
      <div class="item">商家</div>
    </div>
    <div class="content">I am content</div>
  </div>
</template>

<script>

import header from './components/header/header.vue';
export default {
  components: {
    'v-header': header
  }
  // name: 'app'
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
