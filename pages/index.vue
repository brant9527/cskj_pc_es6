<template>
  <div class="container">
    <Header />
    <Banner />
    <Download />
    <Footer />

  </div>
</template>

<script>
import Header from "~/components/Header.vue";
import Banner from "~/components/Banner.vue";
import Footer from "~/components/Footer.vue";
import Download from "~/components/Download.vue";

export default {
  components: {
    Header,
    Banner,
    Footer,
    Download
  }
};
</script>
<style lang="scss" scoped>
.container {
  display: flex;
  flex-direction: column;
}
</style>