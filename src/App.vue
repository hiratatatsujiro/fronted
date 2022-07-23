<template>
  <v-app>
    <v-main>
      <CalendarPage />
    </v-main>
  </v-app>
</template>

<script>
import CalendarPage from "./components/CalendarPage.vue";

export default {
  name: "App",

  components: {
    CalendarPage,
  },

  data: () => ({
    //
  }),
};
</script>
