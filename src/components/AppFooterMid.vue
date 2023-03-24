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
                <div>
                    <div>
                        <h2>DC COMICS</h2>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>

                    <div>
                        <h2>SHOP</h2>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>

                </div>

                <div>
                    <h2>DC</h2>
                    <ul>
                        <li>Terms of use</li>
                        <li>Privacy Policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                
                <div>
                    <h2>SITES</h2>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>

            <div class="right">
                <img src="../../public/img/dc-logo-bg.png" alt="logo big">
            </div>
        </div>

    </div>
</template>

<style lang="scss" scoped>
    .bg {
        background-image: url(../../public/img/footer-bg.jpg);
        background-position: top;
        background-repeat: no-repeat;
        background-size: cover;
        overflow: hidden;
        
        .container {
            width: 70%;
            display: flex;
            justify-content: space-between;
            margin: auto;

            .right {
                position: relative;

                img {
                    position: absolute;
                    right: 0;
                    top: -80px;
                }
            }
            .left {
                display: flex;

                & > div {
                    display: flex;
                    flex-direction: column;
                    margin: 20px 50px 30px 0;
                }

                div {

                    h2 {
                        margin: 20px 0;
                    }
                }

                li {
                    color: gray;
                    padding-bottom: 5px;
                }
            }

            
        }

        
    }

    ul {
        list-style: none;
    }
</style>