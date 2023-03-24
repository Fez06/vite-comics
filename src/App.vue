<script>
    import AppHeader from './components/AppHeader.vue';
    import AppMain from './components/AppMain.vue';
    import AppFooterVue from './components/AppFooter.vue';

    export default {
        components: {
            AppHeader,
            AppMain,
            AppFooterVue
        }
    }
</script>

<template>
    <div class="container">
        <AppHeader/>
        <AppMain/>
        <AppFooterVue/>
    </div>
</template>

<style lang="scss">
    @use './variables.scss' as *;
    

    * {
        @include reset;
    }

</style>
