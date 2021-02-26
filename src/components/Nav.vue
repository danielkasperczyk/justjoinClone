<template>
  <v-container fluid>
    <v-form class="d-flex align-center">
      <v-btn fab small>
        <v-icon>fas fa-search</v-icon>
      </v-btn>
      <v-select
        v-model="selectedLocation"
        class="flex-sm-grow-0 mx-5"
        :items="locations"
      ></v-select>
      <v-select
        v-model="selectedTech"
        class="flex-sm-grow-0"
        :items="tech"
      ></v-select>
    </v-form>
  </v-container>
</template>

<script>
export default {
  name: 'Nav',
  data() {
    return {
      selectedLocation: '',
      selectedTech: '',
      locations: [
        'Warszawa',
        'Kraków',
        'Wrocław',
        'Poznań',
        'Trójmiasto',
        'Śląsk',
      ],
      tech: [
        'HTML',
        'JavaScript',
        'PHP',
        'Ruby',
        'Python',
        'Java',
        '.Net',
        'C',
        'UX/UI',
      ],
    };
  },
};
</script>

<style></style>
