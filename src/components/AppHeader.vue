<script>
    import HeaderMain from './HeaderMain.vue';
    import HeaderNav from './HeaderNav.vue';

    export default{
        name: "AppHeader",
        components:{
            HeaderMain,
            HeaderNav
        }
    }
</script>

<template>
    <HeaderMain></HeaderMain>
    <HeaderNav></HeaderNav>
</template>