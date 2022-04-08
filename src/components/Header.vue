<template>
    <header>
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="logo">
            <div class="menu"></div>
        </div>
        <div class="menu">
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
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent'
}
</script>

<style lang="scss" scoped>
header{
    margin: 0 10% 0 10%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    .logo{
        width: 30%;
        img{
            max-width: 80px;
        }
    }
    .menu{
        display: flex;
        align-items: center;
        width: 70%;
        justify-content: space-around;
        ul{
            display: flex;
            flex-wrap: wrap;
            li{
                padding: 0 10px;
                list-style-type: none;
                font-size: 12px;
                font-weight: 700;
                color: #60686d;
            }
        }
    }
}


</style>