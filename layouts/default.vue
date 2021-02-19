<template>
  <div>
    <navbar />
    <Nuxt />
    <newsletter />
    <foot />
    <xfooter />
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue"
import Newsletter from "~/components/Newsletter.vue";
import Foot from "~/components/Footer.vue";
import Xfooter from "~/components/Xfooter.vue";

export default {
  components: {
    Navbar, Newsletter, Foot, Xfooter
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');
</style>


