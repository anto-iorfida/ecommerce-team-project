<script>
    import AppHeader from './components/AppHeader.vue';
import { store } from './store.js';
import AppLimitedOffer from './components/AppLimitedOffer.vue';
  

export default {
  components: {
    AppLimitedOffer,
    AppHeader,

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
</template>

<style>

</style>