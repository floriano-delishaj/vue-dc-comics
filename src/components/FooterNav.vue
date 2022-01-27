<template>

    <div class="footer-nav">
        <div class="container">
            <div class="section-left">

                <footer-list />

            </div>
            <div class="section-right">

            </div>
        </div>
    </div>

</template>

<script>
    
    import FooterList from '../components/FooterList.vue'

    export default {
        components: {
            FooterList,
        }
    }

</script>

<style lang="scss" scoped>

    @import '@/style/footerNav.scss';

</style>