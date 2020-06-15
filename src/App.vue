<template>
  <div id="app">
    <productList/>
    <hr/>
    <addProductToCart/>
  </div>
</template>

<script>
import productList from './components/productList'
import addProductToCart from './components/ShoppingCart'

export default {
  name: 'app',
  components: {
    productList,
    addProductToCart
  }
}
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
