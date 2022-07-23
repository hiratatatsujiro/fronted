<template>
  <div>
    <v-sheet height="100vh">
      <Calendar />
    </v-sheet>
  </div>
</template>

<script>
import { mapGetters, mapActions } from "vuex";

export default {
  name: "CalenderPage",
  computed: {
    ...mapGetters("events", ["events"]),
  },
  methods: {
    ...mapActions("events", ["fetchEvents"]),
  },
};
</script>

<style></style>
