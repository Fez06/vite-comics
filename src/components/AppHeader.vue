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
            <div>
                <img src="../../public/img/dc-logo.png" alt="logo">
                <!-- <h1>ff</h1> -->
            </div>

            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </div>
    </div>    
</template>

<style lang="scss" scoped>
    @use '../variables.scss' as *;
    //Con Fabio dicevamo che non serviva mettere anche qui' use, eppure ora se lo tolgo da errore!!!!
    // h1 {
    //     color: $footerBlue;
    // }

    .bg {
        background-color: white;
    }
    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 70%;
        margin: 0 auto;
    }

    ul {
        width: 60%;
        list-style: none;
        display: flex;
        justify-content: end;
        margin: 0;

        li {
            margin: 0 10px;
            padding: 60px 0;
        }

        li:nth-child(2) {
            border-bottom: 4px solid $footerBlue;
        }
    }


</style>