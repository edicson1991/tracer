<template>
  <div>
    <Header />

    <template>
      <div></div>
    </template>

    <Footer />
  </div>
</template>
<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Dashboard",
  data() {},
  components: {
    Header,
    Footer,
  },
};
</script>
<style scoped></style>
