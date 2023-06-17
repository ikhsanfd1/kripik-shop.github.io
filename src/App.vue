<template>
  <div id="app">
    <div class="background">
    <router-view />
    <Footer />
    </div>
  </div>
</template>

<script>
import Footer from "@/components/Footer.vue";

export default {
  components: {
    // eslint-disable-next-line vue/no-unused-components
    Footer,
  },
};
</script>
<style>
.background {
  background-image: url("@/assets/images/background.jpg");
  /* Atur properti latar belakang lainnya jika diperlukan */
}
</style>
