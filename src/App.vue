<script>
import AppHeader from './components/AppHeader.vue';
import { store } from './store.js';
import AppLimitedOffer from './components/AppLimitedOffer.vue';
import CardProduct from './components/CardProduct.vue'
import DiscoverProduct from './components/DiscoverProduct.vue';

export default {
  components: {
    AppLimitedOffer,
    AppHeader,
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
    <header>
        <AppHeader></AppHeader>
    </header>
    <main>
      <DiscoverProduct></DiscoverProduct>
      <AppLimitedOffer></AppLimitedOffer>
      <CardProduct></CardProduct>
    </main>
  

</template>

<style lang="scss" >
@use './style/general.scss' as *;
</style>