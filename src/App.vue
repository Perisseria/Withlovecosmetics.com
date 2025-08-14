<template>
  <Navbar />
  <landing />
  <cards />
  <videopart />
  <router-view />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import landing from "./components/landing.vue";
import cards from "./components/cards.vue";
import videopart from "./components/videopart.vue";

export default {
  name: "App",
  components: {
    Navbar,
    landing,
    cards,
    videopart,
  },
};
</script>
