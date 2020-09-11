<template>
  <v-container fluid style="background-color: #cde0e7; border-bottom: 2px solid white">
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto mt-5 align-items-center"
      style="background-color: #cde0e7;"
    >
      <v-row align-content="center">
        <v-col cols="12">
          <v-row>
            <div class="mx-auto text-center">
              <h1
                class="cabecera"
              >4gewinnt Consulting</h1>
              <p
                class="contenido"
                style="color: #d97c30 !important; font-weight: 700 !important;"
              >4gewinnt steht für die vier wesentlichen Bereiche eines erfolgreichen Unternehmens.</p>
            </div>
            <div class="mx-auto">
              <p
                class="contenido"
              >Wir sind seit Jahrzehnten als Entwicklungsfirma und als Vertriebsfirma tätig.</p>
              <p
                class="contenido"
              >Hier entwickeln und konzipieren wir Lösungen für individuelle Projekte/ Anforderungen, als auch für gesamte Standardproduktpaletten.</p>
              <p
                class="contenido"
              >Neben der Entwicklung spielt das Marketing und der Vertrieb eine entscheidende Rolle. Wie mache ich ein Produkt zum Standardprodukt, wie etabliere ich eine Marke, wie akquiriere ich erfolgreich im Projektgeschäft, was macht den Unterschied?</p>
              <p
                class="contenido"
              >Fehler in der Planungsphase kommen später sehr teuer. Meist kann man diese nur sehr schwer oder gar nicht mehr korrigieren.</p>
              <p
                class="contenido"
              >Wie muss die Entwicklungsstruktur sein, welche Vertriebswege sollte ich wählen? Wie sieht der Markt aus wie stark ist der Wettbewerb.</p>
              <p class="contenido">Brauche ich Kapital oder einen Investor?</p>
              <p
                class="contenido"
              >Was ist mit der Infrastruktur, Entwicklung, Support, Buchhaltung, Interne EDV Wie optimiert sind die Prozesse im Bezug auf Kosten Transparenz und Vertrieb</p>
            </div>
            <div class="mx-auto text-center">
              <p
                class="contenido"
                style="color: #d97c30 !important; font-weight: 700 !important;"
              >Die Spitze zu erreichen ist schon schwer, aber da zu bleiben ist noch viel schwerer.</p>
              <v-btn class="mx-auto btn_5" text>Mehr erfahren ...</v-btn>
            </div>
          </v-row>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "consulting",

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
}

.cabecera {
  font-size: 34px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial, sans-serif !important;
  font-weight: 400 !important;
  text-transform: capitalize;
}

.contenido {
  line-height: 1.5em !important;
  font-size: 15px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 400 !important;
  color: #666666 !important;
}
</style>