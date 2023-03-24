<script>
    export default {
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
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '../variables.scss' as *;
    .bg {
        background-color: #1c1c1c;
        .container {
            height: 200px;
            width: 70%;
            margin: auto;
            position: relative;

            h3 {
                color: white;
                padding: 10px 20px;
                background-color: $footerBlue;
                position: absolute;
                top: 0;
                left: 0;
                transform: translate(-0%, -50%);
            }
        }
    }
    
</style>