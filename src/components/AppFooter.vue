<script>
    import AppFooterTopVue from './AppFooterTop.vue';
    import AppFooterMidVue from './AppFooterMid.vue';
    import AppFooterBot from './AppFooterBot.vue';

    export default {
        components: {
            AppFooterTopVue,
            AppFooterMidVue,
            AppFooterBot
        },

        data() {
            return {

            }
        }
    }
</script>

<template>
    <AppFooterTopVue/>
    <AppFooterMidVue/>
    <AppFooterBot/>
</template>

<style lang="scss">
    
</style>