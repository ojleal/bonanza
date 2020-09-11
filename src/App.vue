<template>
  <v-app>
    <v-main>
      <phoneinfo />
      <mainmenu />
      <sliderimg />
      <features />
      <consulting />
      <theory />
      <team />
      <footerpage />
    </v-main>
  </v-app>
</template>

<script>
import phoneinfo from './components/Phoneinfo';
import mainmenu from './components/Menu';
import sliderimg from './components/Slider';
import features from './components/Features';
import consulting from './components/Consulting';
import theory from './components/Theory';
import team from './components/Team';
import footerpage from './components/Footer';

export default {
  name: 'App',

  components: {
    phoneinfo,
    mainmenu,
    sliderimg,
    features,
    consulting,
    theory,
    team,
    footerpage,
  },

  data: () => ({
    //
  }),
};
</script>