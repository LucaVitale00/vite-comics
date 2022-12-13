<script>
import Jumbotron from './JumbotronItem.vue'
import SiteUpFooter from './SiteUpFooter.vue';
import ComicsList from './ComicsList.vue';

export default {
    name: "SiteMain",
    components: {
        SiteUpFooter,
        Jumbotron,
        ComicsList
    }
}

</script>
<template>

    <main id="site_main">
        <Jumbotron />

        <ComicsList />

        <SiteUpFooter />
    </main>

</template>

<style lang="scss" scoped>

</style>