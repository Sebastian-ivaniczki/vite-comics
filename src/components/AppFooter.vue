<script>
export default {
    name: 'AppFooter',
    data() {
        return {

        }
    }
}
</script> 

<template>
    <div class="foot">
        <div class="container">
            <div class="row">
                <div class="col-left">
                    <button><a href="#">SIGN-UP NOW!</a></button>
                </div>
                <div class="col-right">
                    <div>
                        <h3>FOLLOW US</h3>
                    </div>
                    <figure>
                        <a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a>
                        <a href="#"><img src="../assets/img/footer-twitter.png" alt="facebook"></a>
                        <a href="#"><img src="../assets/img/footer-youtube.png" alt="facebook"></a>
                        <a href="#"><img src="../assets/img/footer-pinterest.png" alt="facebook"></a>
                        <a href="#"><img src="../assets/img/footer-periscope.png" alt="facebook"></a>
                    </figure>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.foot{
    height: 135px;
    background-color: #303030;
}
.container{
    height: 100%;
}
.row{
    height: 100%;
    display: flex;
    align-items: center;
}
.col-left {
    width: 70%;
}
.col-right {
    width: 30%;
    color: #0282F9;
    display: flex;
    align-items: center;
}
button{
    background-color: #303030;
   

    a{
        display: inline-block;
        color: #fff;
        padding: 1rem;
        border: 2px solid #0282F9;
    }
}
figure{
    display: flex;
    margin-left: 15px;

    a{
        margin-right: 10px;
        img{
            display: block;
        }
    }
}
</style>