<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main>
      <DotaHero/>
    </v-main>
  </v-app>
</template>

<script>
import DotaHero from "@/components/DotaHero";
export default {
  name: 'App',

  components: {
    DotaHero
  },

  data: () => ({
    //
  }),
};
</script>
