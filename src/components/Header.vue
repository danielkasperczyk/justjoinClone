<template>
  <v-layout align-center justify-space-between>
    <h2>justget.it</h2>
    <v-switch
      label="Dark mode"
      v-model="$vuetify.theme.dark"
      hide-details
    ></v-switch>
  </v-layout>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style></style>
