<script>
import SiteHeader from './components/SiteHeader.vue';
import SiteFooter from './components/SiteFooter.vue';

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteFooter
  }

}
</script>

<template>
  <SiteHeader></SiteHeader>
  <!-- /#site_header -->
  <SiteFooter></SiteFooter>
  <!-- /#site_footer -->

</template>

<style>

</style>