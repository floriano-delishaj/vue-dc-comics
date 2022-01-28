<template>
    
    <main>


        <div class="container">

        <div class="current-series">
            current series
        </div>

            <div class="row">
                <div class="col-2 pt-3" v-for="(card, i) in comics" :key="i">
                    <div class="card-box">
                        <div class="card-img">
                            <img :src="card.thumb" alt="">
                        </div>
                        <p>{{card.series}}</p>
                    </div>
                </div>
            </div>
        </div>
    </main>

</template>

<script>
    export default {
        props: {
            comics: Array
        }
    }
</script>

<style lang="scss" scoped>

@import '@/style/mainCards.scss';

</style>