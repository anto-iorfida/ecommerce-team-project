<script>
import { store } from './store.js';
import AppLimitedOffer from './components/AppLimitedOffer.vue';
import CardProduct from './components/CardProduct.vue'

export default {
  components: {
    AppLimitedOffer,
    CardProduct
  },

  data() {
    return {
      store
    };
  },
  
  methods: {
   
  },
  mounted() {
   
  }
}
</script>

<template>
  <AppLimitedOffer></AppLimitedOffer>
  <CardProduct></CardProduct>
</template>

<style scoped lang="scss" >
   @use './style/general' as *;
</style>