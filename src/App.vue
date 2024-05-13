<script>
import { store } from './store.js';
import AppLimitedOffer from './components/AppLimitedOffer.vue';
import CardProduct from './components/CardProduct.vue'
import DiscoverProduct from './components/DiscoverProduct.vue';

export default {
  components: {
    AppLimitedOffer,
    CardProduct,
    DiscoverProduct,

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
<DiscoverProduct></DiscoverProduct>
<AppLimitedOffer></AppLimitedOffer>
</template>

<style lang="scss" >
@use './style/general.scss' as *;
</style>