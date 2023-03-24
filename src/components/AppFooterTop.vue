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
        <ul>
            <li>
                <img src="../../public/img/buy-comics-digital-comics.png" alt="digital comics">
                <span>DIGITAL COMICS</span>
            </li>
            <li>
                <img src="../../public/img/buy-comics-merchandise.png" alt="comics merchandise">
                <span>COMICS MERCHANDISE</span>
            </li>
            <li>
                <img src="../../public/img/buy-comics-subscriptions.png" alt="subscriptions">
                <span>SUBSCRIPTIONS</span>
            </li>
            <li>
                <img src="../../public/img/buy-comics-shop-locator.png" alt="shop-locator">
                <span>SHOP LOCATOR</span>
            </li>
            <li>
                <div class="svg-container">
                    <img class="svg" src="../../public/img/buy-dc-power-visa.svg" alt="dc power visa">
                </div>
                <span>DC POWER VISA</span>
            </li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
    @use '../variables.scss' as *;
    .bg {
        background-color: $footerBlue;

        ul {
            height: 100%;
            width: 70%;
            margin: auto;
            display: flex;
            justify-content: space-evenly;
            padding: 30px 0;

            li {
                list-style: none;
                width: calc(100% / 5);
                display: flex;
                justify-content: center;
                align-items: center;

                & * {
                    color: white;
                    
                }

                .svg-container {
                    list-style: none;
                    width: calc(100% / 5);
                    display: flex;
                    justify-content: center;
                    align-items: center;

                    .svg {
                        width: 100%;
                        height: auto;
                    }
                }
                
                img {
                    height: 70%;
                }
                
                span {
                    margin-left: 20px;
                }

            }
        }
    }
</style>