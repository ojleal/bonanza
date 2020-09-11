<template>
  <v-carousel cycle height="400" hide-delimiter-background show-arrows-on-hover>
    <v-carousel-item
      v-for="(slide, i) in slides"
      :key="i"
      interval="5000"
      reverse-transition="fade-transition"
      transition="fade-transition"
    >
      >
      <v-sheet :src="slides" height="100%">
        <v-row class="fill-height" align="bottom" justify="left">
          <div class="display-3">
            Die 4gewinnt Consulting
            <br />
            {{ slide }}
          </div>
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
</template>


<script>
export default {
  name: "slider",
  data() {
    return {
      slides: [
        "Alles dreht sich um Sie",
        "Beratung und Umsetzung für Ihren Erfolg!",
        "Ein Feuerwerk für Ihr Unternehmen",
      ],
      items: [
        {
          src: "./koeln-bei-nacht-deutzer-kirmes.jpg",
        },
        {
          src: "./koeln-bei-nacht-unter-der-severinsbruecke.jpg",
        },
        {
          src: "./Koelner-Lichter-2019-7590.jpg",
        },
      ],
    };
  },
};
</script>