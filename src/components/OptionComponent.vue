<template>
<section>

    <div class="container">
        <div class="row">
            
             <div class="col-2">
                <div>
                    <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
                    <a href="#">digital comics</a>
                </div>
            </div>
            <div class="col-2">
                <div>
                    <img src="@/assets/img/buy-comics-merchandise.png" alt="">
                    <a href="#">dc merchandise</a>
                </div>
            </div>
            <div class="col-2">
                <div>
                    <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
                    <a href="#">subscriptions</a>
                </div>
            </div>
            <div class="col-2">
                <div>
                    <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
                    <a href="#">comic shop locator</a>
                </div>
            </div>
            <div class="col-2">
                <div>
                    <img src="@/assets/img/buy-dc-power-visa.svg" alt="">
                    <a href="#">dc power visa</a>
                </div>
            </div>
            
        </div>

    </div>
</section>
</template>

<script>
export default {
    name: 'OptionComponent'
}
</script>

<style lang="scss" scoped>

.container{
    width: 1000px;
    margin: auto;
}

.row{
    display: flex;
    align-items: center;
    justify-content: center;
    column-gap: 30px;
}
.col-2>div {
    display: flex;
    align-items: center;
    justify-content: center;    
    column-gap: 6px;
}
section {
    background-color: #0282F9;;
    padding: 35px 15px;
}

a {
    text-decoration: none;
    color: white;
    text-transform: uppercase;
    font-size: 10px;
}
img {
    max-width: 40px;
    aspect-ratio: 1.1;
    object-fit: contain;
}

</style>
