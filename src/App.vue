<template>
  <div id="app">
    <router-view />
    <Footer />
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