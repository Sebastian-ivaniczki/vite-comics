<script>
export default {
    name: 'AppHeader',
    data() {
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
  {
    text: 'Shop',
    url: '#',
    current: false,
  },
]

        }
    }
}
</script> 

<template>
    <header>
        <nav class="container">
            <div class="nav_left">
                <img src="../assets/img/dc-logo.png" alt="logo dc">
            </div>
            <div class="nav_right">
                <ul>
                    <li v-for="link in links" :key="link.text">
                        <a :class="{'active' : link.current}" :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
nav {
    height: 130px;
    display: flex;
}
.nav_left {
width: 40%;
height: 100%;

display: flex;
align-items: center;
}
.nav_right {
    width: 60%;
    height: 100%;
    
}
 ul {
    height: 100%;
    display: flex;
    align-items: center; 
  li {
    list-style-type: none;
}
}
a {
    padding: 0.45rem;
    padding-bottom: 1rem;
    display: inline-block;
}
a:hover{
    color: #0282F9;
    border-bottom:3px solid #0282F9 ;
}
.active {
    color: #0282F9;
    border-bottom:3px solid #0282F9 ;
}
</style>