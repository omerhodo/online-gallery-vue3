<template>
  <Navbar />
  <div class="container">
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/home/HomeNavbar.vue";

export default {
  name: "HomeView",
  components: { Navbar },
};
</script>
