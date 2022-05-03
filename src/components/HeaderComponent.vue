<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="col-4">
                    <img src="@/assets/img/dc-logo.png" alt="logo">
                </div>
                <div class="col-8">
                     <nav>
                        <ul>
                            <li>characters</li>
                            <li class="active">comics</li>
                            <li>movies</li>
                            <li>tv</li>
                            <li>games</li>
                            <li>collectibles</li>
                            <li>videos</li>
                            <li>fans</li>
                            <li>news</li>
                            <li>shop</li>
                        </ul>
                     </nav>
                </div>
            </div>
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
       .container{
           margin: auto;
           width: 1300px;
       }

       .row{
           display: flex;  
           align-items: center;
           justify-content: space-around;
       }
       img{
           width: 70px;
       }
    }

    nav{
        ul{
            list-style: none;

            li{
                display: inline-block;
                text-transform: uppercase;
                padding: 32px 10px;
                font-size: 14px;
                font-weight: 700;
            }
        }
    }

    .active {
    color: blue;
    position: relative;
}
.active:before {
  content: "";
  position: absolute;
  left: 50%;
  bottom: 0;
  width: 50%; 
  height: 1px;
  transform: translate(-50%,-50%);
  border-bottom: 2px solid blue;
}
   
</style>