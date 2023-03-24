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
            <div class="left">
                <button>SIGN-UP NOW!</button>
            </div>

            <div class="right">
                <h3>FOLLOW US</h3>
                <img src="../../public/img/footer-facebook.png" alt="facebook">
                <img src="../../public/img/footer-twitter.png" alt="twitter">
                <img src="../../public/img/footer-youtube.png" alt="youtube">
                <img src="../../public/img/footer-pinterest.png" alt="pinterest">
                <img src="../../public/img/footer-periscope.png" alt="periscope">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '../variables.scss' as *;

    .bg {
        background-color: black;
    }
    .container {
        width: 70%;
        display: flex;
        padding: 30px 0;
        margin: auto;
        justify-content: space-between;
        

        .left {
            button {
                background: none;
                color: white;
                border: 2px solid $footerBlue;
                padding: 10px;
                font: inherit;
                cursor: pointer;
            }
        }

        .right {
            display: flex;
            text-align: center;

            h3 {
                color: $footerBlue;
                margin-right: 20px;
                white-space: nowrap;
                align-self: center;
            }

            img {
                margin-left: 20px;
                color: gray;
                height: 100%;
                width: auto;
            }
        }
    }
</style>