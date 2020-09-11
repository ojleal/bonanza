<template>
  <v-app-bar app color="primary" dark elevate-on-scroll="true">
    <div class="d-flex align-center">
      <v-img
        alt="Bonanza Logo"
        class="shrink mr-2"
        contain
        src="Logo_4gewinnt-1-300x85.png"
        transition="scale-transition"
        width="200"
      />
    </div>

    <v-spacer></v-spacer>
    <div class="botones">
      <v-btn text rounded>Startseite</v-btn>
      <v-btn text rounded>Planung</v-btn>
      <v-btn text rounded>Entwicklung</v-btn>
      <v-btn text rounded>Vertrieb</v-btn>
      <v-btn text rounded>Struktur</v-btn>
      <v-btn text rounded>Über uns</v-btn>
      <v-btn
        text
        style="background: #009c41; color: #ffffff !important;"
        class="botones2"
      >Corona News</v-btn>
      <v-btn
        text
        style="background: #3c5586; color: #ffffff !important;"
        class="botones2"
      >Beratungstermin</v-btn>
      <v-btn text style="background: #3c5586; color: #ffffff !important;" class="botones2">Kontakt</v-btn>
    </div>
  </v-app-bar>
</template>

<script>
export default {
  name: "mainmenu",
  data() {
    return {};
  },
};
</script>


<style>
.botones .v-btn {
  color: #61615f !important;
  font-size: 13px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 600 !important;
  text-transform: capitalize !important;
  padding-top: 0px !important;
  padding-right: 8px !important;
  padding-bottom: 0px !important;
  padding-left: 8px !important;
}

.v-btn.botones2 {
  width: 140px;
  padding-right: 16px !important;
  padding-left: 16px !important;
  margin-right: 5px !important;
}

.v-btn {
  letter-spacing: 0px !important;
  line-height: 88px !important;
}

.v-btn.botones2 :hover {
  text-decoration: none;
}

.botones.v-btn :hover {
  background-color: #cde0e7;
}
</style>