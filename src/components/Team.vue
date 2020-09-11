<template>
  <v-container
    fluid
    style="background-color: #f2f2f2; border-top: 2px solid white; border-bottom: 2px solid #d97c30"
  >
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto mt-5 align-items-center"
      style="background-color: #f2f2f2;"
    >
      <v-row align-content="center">
        <v-col cols="12">
          <v-row>
            <div class="mx-auto text-center">
              <h1
                class="encabezado"
                style="font-size: 34px !important; font-weight: 400 !important"
              >Unser Team</h1>
            </div>
          </v-row>
        </v-col>
      </v-row>
      <v-row align-content="center">
        <v-col class="mx-auto text-center" cols="12">
          <v-icon color="#d97c30" x-large>fas fa-minus</v-icon>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="6">
          <v-img
            src="../assets/Mitarbeiter_gesucht_3.png"
            max-width="600px"
            max-height="402px"
            class="mx-auto"
          ></v-img>
        </v-col>
        <v-col cols="6">
          <v-card
            outlined
            tile
            class="mx-auto mt-5 align-items-center"
            style="background-color: #f2f2f2;"
          >
            <v-list-item tile>
              <div class="mx-auto text-center encabezado">Mitarbeiter gesucht</div>
            </v-list-item>
            <div class="mx-auto text-center contenido">
              <p>Unser Produkt wächst stetig weiter und so soll auch unser Team weiterhin wachsen. An neuen Kollegen und Kolleginnen, Erfahrung und Wissen. Zur Zeit suchen wir Unterstützung in den folgenden Bereichen:</p>
              <p>Vertrieb</p>
              <p style="color: #d97c30 !important">Vertriebsaußendienst für Deutschland (w/m)</p>
              <p>Entwicklung</p>
              <p
                style="color: #d97c30 !important"
              >Developer PHP und Angular (w/m), Front-End Development (w/m), Webdesigner/in, Projektmanagement IT (w/m)</p>
              <p>Falls wir Dein Interesse geweckt haben und Du Lust hast bei uns mitzuarbeiten (auch wenn Dich keine der genannten Positionen anspricht), freuen wir uns auf Deine Bewerbung.</p>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "team",

  data() {
    return {};
  },
};
</script>

<style>
.btn_1 {
  background-color: #d97c30;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
}

.btn_2 {
  background-color: #009c41;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
}

.btn_3 {
  background-color: #1f7891;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
}

.btn_4 {
  background-color: #662575;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
}

.btn_5 {
  background-color: #3c5586;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
}

.subtitulo {
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 18px !important;
  text-transform: capitalize !important;
  font-weight: 400 !important;
}

.group {
  display: flex;
  flex: 1;
  justify-content: space-around;
}

.divisor {
  border-color: #ffffff !important;
}

.v-sheet.v-card {
  border-radius: 10px !important;
}

.card_1.v-card {
  border-color: #009c41 !important;
}

.encabezado {
  font-size: 23px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 700 !important;
  color: #d97c30 !important;
  text-transform: uppercase;
}

.contenido {
  line-height: 1.5em !important;
  font-size: 15px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 400 !important;
}
</style>