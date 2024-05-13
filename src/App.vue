<script>
    import AppHeader from './components/AppHeader.vue';
import { store } from './store.js';
import AppLimitedOffer from './components/AppLimitedOffer.vue';
import CardProduct from './components/CardProduct.vue';

export default {
  components: {
    AppLimitedOffer,
    AppHeader,

    CardProduct,
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
  <AppLimitedOffer></AppLimitedOffer>
  <CardProduct></CardProduct>
</template>

<style scoped lang="scss" >
   @use './style/general' as *;
</style>