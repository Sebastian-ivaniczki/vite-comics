<script>
export default {
    name: 'AppMain',
    data()
 {
    return {
        links: [
  {
    text: 'Characters',
    url: '#',
    current: false,
  },
  {
    text: 'Comics',
    url: '#',
    current: true,
  },
  {
    text: 'Movies',
    url: '#',
    current: false,
  },
  {
    text: 'TV',
    url: '#',
    current: false,
  },
  {
    text: 'Games',
    url: '#',
    current: false,
  },
  {
    text: 'Collectibles',
    url: '#',
    current: false,
  },
  {
    text: 'Videos',
    url: '#',
    current: false,
  },
  {
    text: 'Fans',
    url: '#',
    current: false,
  },
  {
    text: 'News',
    url: '#',
    current: false,
  },
 
]
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
                <div class="col mt">
                    <div>
                        <div>
                            <h5>DC STORE</h5>
                        </div>
                        <ul>
                            <li v-for="link in links" :key="link.text">
                                <a :href="link.url">{{ link.text }}</a>
                            </li>
                        </ul>
                        <div class="mt">
                            <h5>SHOP</h5>
                            <ul>
                                <li><a href="#">Shop DC</a></li>
                                <li><a href="#">Shop DC collectibles</a></li>
                            </ul>
                        </div>

                    </div>
                    <div>
                        <h5>DC</h5>
                        <ul>
                                <li><a href="#">Therm of use</a></li>
                                <li><a href="#">Privacy policy (New)</a></li>
                                <li><a href="#">ADD Choices</a></li>
                                <li><a href="#">Advertisign</a></li>
                                <li><a href="#">jobs</a></li>
                                <li><a href="#">Subscriptions</a></li>
                                <li><a href="#">Talent Workshops</a></li>
                                <li><a href="#">CPSC Certifications</a></li>
                                <li><a href="#">Ratings</a></li>
                                <li><a href="#">Shop Help</a></li>
                                <li><a href="#">Contacts US</a></li>
                        </ul>
                    </div>
                    <div>
                            <h5>SITES</h5>
                            <ul>
                                <li><a href="#">DC</a></li>
                                <li><a href="#">MAD Magazine</a></li>
                                <li><a href="#">DC Kids</a></li>
                                <li><a href="#">DC Universe</a></li>
                                <li><a href="#">DC Power Visa</a></li>
                            </ul>
                    </div>
                </div>
                <div class="col">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.mt{
    margin-top: 2rem;

}

.content {
    height: 130px;
    background-color: #000;
    color: #fff;
}

h3{
   line-height: 130px; 
}
.jumbotron{
    color: #fff;
    background-image: url(../assets/img/footer-bg.jpg);
    height: 350px;
}
.row {
    display: flex;
}
.col {
    width: 50%;
    display: flex;
    div{
        margin-right: 15px;
    }
}
img{
    height: 350px;
}
ul{
    margin-top: 10px;
    li {
       list-style-type: none; 
       
       a {
        color: #878868;
        font-size: xx-small;
       }
    }
}
</style>