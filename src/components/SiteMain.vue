<script>
import Jumbotron from './JumbotronItem.vue'
import SiteUpFooter from './SiteUpFooter.vue';


export default {
    name: "SiteMain",
    components: {
        SiteUpFooter,
        Jumbotron,

    }
}

</script>
<template>

    <main id="site_main">
        <Jumbotron />



        <SiteUpFooter />
    </main>

</template>

<style lang="scss" scoped>

</style>