<script>
    export default {
        name: 'card',
        props: {
            thumb: String,
            series: String            
        },

        data() {
            return {

            }
        }
    }
</script>

<template>
    <div class="box">
        <img :src="thumb">
        <div class="serie">{{ series }}</div>
    </div>
</template>

<style lang="scss" scoped>
    @use '../variables.scss' as *;
    
    .box {
        height: 250px;
        width: 190px;
        margin: auto;
        text-align: center;

        img {
            max-height: 80%;
            width: auto;
        }

        .serie {
            inline-size: 140px;
            overflow-wrap: break-word;
            font-size: 12px;
        }
    }
</style>