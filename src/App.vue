<template>
  <v-app>
    <nav-bar />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import NavBar from "./components/NavBar.vue";

export default {
  components: { NavBar },
  name: "App",

  data: () => ({
    NavBar,
  }),
};
</script>
