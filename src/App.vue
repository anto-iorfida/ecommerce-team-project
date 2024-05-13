<script>
import { store } from './store.js';
import AppLimitedOffer from './components/AppLimitedOffer.vue';
  

export default {
  components: {
    AppLimitedOffer,

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
</template>

<style>

</style>