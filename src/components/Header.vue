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
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    .menu{
        display: flex;
        align-items: center;
        ul{
            display: flex;
            li{
                list-style-type: none;
            }
        }
    }
}


</style>