<template>
  <v-app
    id="inspire"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <Sidebar />
  </v-app>
</template>

<script>
// import HelloWorld from '../components/HelloWorld';
import Sidebar from '../components/Sidebar.vue';
// import { Carousel3d, Slide } from 'vue-carousel-3d';

export default {
  data: () => ({
    slides: [
      { src: require('../../public/12.jpg'), text: 'Cheb Khaled' },
      { src: require('../../public/02.jpeg'), text: 'Sooling' },
      { src: require('../../public/03.png'), text: 'Chakira' },
    ],
  }),
  components: {
    Sidebar,
    // Carousel3d,
  },
};
</script>
