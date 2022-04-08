<template>
    <div class="jumbotron">
        <div class="jumbotron_cover">
            <img src="../assets/img/jumbotron.jpg" alt="jumbotron">
            <div class="menu"></div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'JumbotronComponent'
}
</script>

<style lang="scss" scoped>
    .jumbotron_cover{
        height: 300px;
        img{
            height: 100%;
            object-fit: cover;
            width: 100vw;
            object-position: 0% 0%;
        }
    }

</style>