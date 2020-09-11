<template>
  <v-carousel height="698px" cycle continuous interval="4000" hide-delimiter-background show-arrows-on-hover>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      interval="5000"
      reverse-transition="fade-transition"
      transition="fade-transition"
    >
      <v-container fill-height mb-10>
        <v-row>
          <v-col cols="12">
            <v-card color="transparent" outlined tile>
              <v-card-title>
                <p class="titulo">Die 4gewinnt Consulting</p>
              </v-card-title>
              <v-card-subtitle class="sub-titulo">
                <span v-text="item.txt"></span>
              </v-card-subtitle>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-carousel-item>
  </v-carousel>
</template>



<script>
export default {
  name: "Slider",

  data() {
    return {
      items: [
        {
          src: "./koeln-bei-nacht-deutzer-kirmes.jpg",
          txt: "Alles dreht sich um Sie",
        },
        {
          src: "./koeln-bei-nacht-unter-der-severinsbruecke.jpg",
          txt: "Beratung und Umsetzung für Ihren Erfolg!",
        },
        {
          src: "./Koelner-Lichter-2019-7590.jpg",
          txt: "Ein Feuerwerk für Ihr Unternehmen",
        },
      ],
    };
  },
};
</script>

<style>
.titulo {
  font-size: 45px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 400 !important;
}

.sub-titulo {
  font-size: 23px !important;
  color: #ffffff !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 700 !important;
}

.container.fill-height {
  align-content: end !important;
}
</style>