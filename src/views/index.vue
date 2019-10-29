<template>
  <div class="home">
    <Banner />
    <Purpose />
    <Services />
  </div>
</template>

<script>
import Banner from "../components/home/Banner";
import Purpose from "../components/home/Purpose";
import Services from "../components/home/Services";
export default {
  name: "home",
  components: {
    Banner,
    Purpose,
    Services
  },
  activated(v) {
    console.log(v);
  },
  mounted() {
    console.log(this.$route);
  }
};
</script>
