<template>
  <div id='app'>
    <product-list-one v-bind:products='products'></product-list-one>
    <product-list-two v-bind:products='products'></product-list-two>
  </div>
</template>

<script>
import ProductListOne from './components/productListOne.vue';
import ProductListTwo from './components/productListTwo.vue';
export default {
  components: {
    'product-list-one': ProductListOne,
    'product-list-two': ProductListTwo
  },
  name: 'app',
  data () {
    return {

    }
  }
}
</script>

<style>
</style>
