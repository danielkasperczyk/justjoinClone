<template>
  <v-app>
    <v-app-bar flat app>
      <Header />
    </v-app-bar>
    <v-main>
      <Nav />
    </v-main>
  </v-app>
</template>

<script>
import Header from '@/components/Header.vue';
import Nav from '@/components/Nav.vue';

export default {
  name: 'App',

  components: {
    Header,
    Nav,
  },

  data: () => ({
    //
  }),
};
</script>
