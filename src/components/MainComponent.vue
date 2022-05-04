<template>
    <main>
        <div class="jumbotron">
            <img src="" alt="">
        </div>
       <div class="container">

       </div>
    </main>
</template>

<script>
export default {
    name: 'MainComponent'
}
</script>

<style lang="scss" scoped>

main{
    background-color: black;
    width: 100vw;
    height: 600px;
    .jumbotron{
        background-image: url('@/assets/img/jumbotron.jpg');
        background-size: cover;
        width: 100%;
        height: 300px;

    }
}

</style>
