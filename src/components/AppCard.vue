<script>
export default {
    name: 'ComicsCard',
    props: {
        card: Object,
        
    }
}
</script>

<template>
     <div class="card">
            <img :src="card.thumb" :alt="card.series">
            <h4>{{ card.series }}</h4>
    </div>
</template>

<style lang="scss" scoped>

.card{
    
    flex-basis: calc(100% / 6);
    padding: 10px;
    color: #fff;
    margin-bottom: 10px;
   img{
    height: 100%;
   }
}</style>