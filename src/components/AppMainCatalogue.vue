<script>
    import AppCards from './AppCards.vue';
    import AppMainCatalogueList from './AppMainCatalogueList.vue';

    export default {
        components: {
            AppCards,
            AppMainCatalogueList
        },

        data() {
            return {
                
            }
        }
    }
</script>

<template>
    <div class="bg">
        <div class="container">
            <h3>CURRENT SERIES</h3>
            <AppMainCatalogueList/>
            <button>LOAD MORE</button>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '../variables.scss' as *;
    .bg {
        background-color: #1c1c1c;
        .container {
            width: 70%;
            margin: auto;
            position: relative;
            text-align: center;

            h3 {
                color: white;
                padding: 10px 20px;
                background-color: $footerBlue;
                position: absolute;
                top: 0;
                left: 0;
                transform: translate(-0%, -50%);
            }

            button {
                background-color: $footerBlue;
                border: 0;
                margin-bottom: 10px;
                padding: 15px 60px;
            }
        }
    }
    
</style>