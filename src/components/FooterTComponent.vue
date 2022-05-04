<template>
    <section class="top">
        <div class="container">
            <div class="row">
                <div class="col-6">

                    <div class="row">
                        <div class="col-4">
                            <h4>dc comics</h4>
                                <ul>
                                    <li><a href="#">Characters</a></li>
                                    <li><a href="#">Comics</a></li>
                                    <li><a href="#">Movies</a></li>
                                    <li><a href="#">TV</a></li>
                                    <li><a href="#">Games</a></li>
                                    <li><a href="#">Videos</a></li>
                                    <li><a href="#">News</a></li>
                                </ul>
                                <h4>shop</h4>
                                <ul>
                                    <li><a href="#">Shop DC</a></li>
                                    <li><a href="#">Shop DC Collectibles</a></li>
                                </ul>
                        </div>

                        <div class="col-4">
                            <h4>dc</h4>
                            <ul>
                                <li><a href="#">Terms Of Use</a></li>
                                <li><a href="#">Privacy policy (New)</a></li>
                                <li><a href="#">ad Choices</a></li>
                                <li><a href="#">Advertising</a></li>
                                <li><a href="#">Jobs</a></li>
                                <li><a href="#">Subscriptions</a></li>
                                <li><a href="#">Talent Workshops</a></li>
                                <li><a href="#">CPSC Certificates</a></li>
                                <li><a href="#">Ratings</a></li>
                                <li><a href="#">Shop Help</a></li>
                                <li><a href="#">Contact Us</a></li>
                            </ul>
                        </div>

                        <div class="col-4">
                            <h4>sites</h4>
                            <ul>
                                <li><a href="#">DC</a></li>
                                <li><a href="#">MAD Magazine</a></li>
                                <li><a href="#">DC Kids</a></li>
                                <li><a href="#">DC Universe</a></li>
                                <li><a href="#">DC Power Visa</a></li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="col-6">
                    <img src="@/assets/img/dc-logo-bg.png" alt="">
                </div>

            </div>
        </div>
    </section>
</template>

<script>
export default {
   name: 'FooterTComponent' 
}
</script>

<style lang="scss" scoped>
    .top{
        background-image: url('@/assets/img/footer-bg.jpg');
        background-size: cover;
        background-position: center;
    }
    .col-6 img{
        width: 400px;
    }

    ul{
        list-style: none;
        line-height: 20px;
        li{
            text-align: left;
            font-size: 13px;
            a{
                text-decoration: none;
                color: gray;
               
            }
        }
    }

    h4{
      text-transform: uppercase; 
      font-weight: 600;
      color: white;
      margin: 20px 0;
      text-align: left; 
    }

    .col-6{
        padding: 30px 0;
    }

</style>
