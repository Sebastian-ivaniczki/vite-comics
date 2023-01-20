<script>
export default {
    name: 'AppMain',
    data()
 {
    return {

    }
 }}
</script>

<template>
    <div class="content">
        <div class="container">

            <h3>Content goes here</h3>
        </div>
    </div>
    <div class="jumbotron">
        <div class="container">
            <div class="row">
                <div class="col">
                    <ul>
                        <li>
                            <a href=""></a>
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
 .content {
    height: 130px;
    background-color: #000;
    color: #fff;
}

h3{
   line-height: 130px; 
}
.jumbotron{
    background-image: url(../assets/img/footer-bg.jpg);
    height: 350px;
}
.row {
    display: flex;
}
.col {
    width: 50%;
}
img{
    height: 350px;
}

</style>