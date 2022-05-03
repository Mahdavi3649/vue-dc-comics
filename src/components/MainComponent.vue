<template>
    <main>
       <div class="container">
           <h3> --- Content goes here --- </h3>
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
    padding: 2rem; 
    .container{
        width: 1000px;
        margin: auto;
    }
    
    h3{
        color: white;
        text-align: left;
    }
}

</style>
