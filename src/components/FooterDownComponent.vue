<template>
    <footer class="down">

        <div class="container">
            <div class="row">
                <div class="col-4">
                    <button>Sign up now</button>
                </div>

                <div class="col-8">
                    <h3>follow us</h3>
                    <img src="@/assets/img/footer-facebook.png" alt="">
                    <img src="@/assets/img/footer-twitter.png" alt="">
                    <img src="@/assets/img/footer-youtube.png" alt="">
                    <img src="@/assets/img/footer-pinterest.png" alt="">
                    <img src="@/assets/img/footer-periscope.png" alt="">

                </div>
            </div>
        </div>

    </footer>
</template>

<script>
export default {
   name: 'FooterDownComponent' 
}
</script>


<style lang="scss" scoped>

.down{
    background-color: #303030;
    padding: 30px 20px;
    height: 100px;
}

h3 {
    text-transform: uppercase;
    font-weight: 700;
    color: #0282F9;
}
button {
    text-transform: uppercase;
    color: white;
    background-color: transparent;
    padding: 10px 20px;
    font-weight: 600;
    border: 2px solid #0282F9;
}
.col-8 {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    column-gap: 1rem;
}
    
</style>