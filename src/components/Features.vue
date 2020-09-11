<template>
  <v-container
    fluid
    style="background-color: #cde0e7; border-bottom: 2px solid white; border-top: 2px solid white"
  >
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto mt-5 align-items-center"
      style="background-color: #cde0e7;"
    >
      <v-row>
        <v-col cols="3">
          <v-card
            class="mx-auto card_1"
            raised
            rounded-lg
            style="border: 3px solid #d97c30 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div class="mb-1 text-center encabezado">PLANUNG</div>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-img
                  src="../assets/022-presentation-300x300.png"
                  aspect-ratio="1"
                  max-width="120px"
                  class="mx-auto"
                ></v-img>
                <v-divider class="my-4 divisor" light></v-divider>
                <h4 class="mb-4 text-center subtitulo">Der simple Einstieg</h4>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                  >Ihr Einstieg in das Mid-und BackOffice von Bonanza Software. Unsere Empfehlung für Kleinstreisebüros mit geringen Ansprüchen an die Funktionalität, die aber keine Abstriche bei der Qualität machen wollen. Ideal auch für Neugründer.</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="mt-5 divisor" :inset="inset"></v-divider>
            <v-card-actions>
              <v-btn class="mx-auto btn_1" text>Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
        <v-col cols="3">
          <v-card
            class="mx-auto card_1"
            raised
            rounded-lg
            style="border: 3px solid #009c41 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div class="mb-1 text-center encabezado">ENTWICKLUNG</div>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-img
                  src="../assets/007-files-300x300.png"
                  aspect-ratio="1"
                  max-width="120px"
                  class="mx-auto"
                ></v-img>
                <v-divider class="my-4 divisor" light></v-divider>
                <h4 class="mb-4 text-center subtitulo">Viel Funktion bei höchster Qualität</h4>
                <v-divider class="my-2 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                  >Kann alles! Nur Buchhaltung ist nicht sein Ding. Unsere Empfehlung für touristische Reisebüros, die ihre Buchhaltung ausgelagert haben. Durch verschiedene Module kann er sich jederzeit auf Ihre individuellen Bedürfnisse anpassen.</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="mt-4 divisor" :inset="inset"></v-divider>
            <v-card-actions>
              <v-btn class="mx-auto btn_2" text>Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
        <v-col cols="3">
          <v-card
            class="mx-auto card_1"
            raised
            rounded-lg
            style="border: 3px solid #1f7891 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div class="mb-1 text-center encabezado">VERTRIEB</div>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-img
                  src="../assets/038-promotion-300x300.png"
                  aspect-ratio="1"
                  max-width="120px"
                  class="mx-auto"
                ></v-img>
                <v-divider class="my-4 divisor" light></v-divider>
                <h4 class="mb-4 text-center subtitulo">Erfahren und immer einen Schritt voraus</h4>
                <v-divider class="my-2 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                  >Die Version mit Buchhaltung. Ob Firmendienst, IATA Büro oder Leisure Travel – Adam kanns. Auch er passt sich auf Wunsch, durch verschiedene Zusatzmodule, noch näher an Ihre Bedürfnisse an. Das CRM hilft Ihnen bei der Kundenbindung.</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="mt-4 divisor" :inset="inset"></v-divider>
            <v-card-actions>
              <v-btn class="mx-auto btn_3" text>Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
        <v-col cols="3">
          <v-card
            class="mx-auto card_1"
            raised
            rounded-lg
            style="border: 3px solid #662575 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div class="mb-1 text-center encabezado">STRUKTUR</div>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-img
                  src="../assets/puzzle-300x300.png"
                  aspect-ratio="1"
                  max-width="120px"
                  class="mx-auto"
                ></v-img>
                <v-divider class="my-4 divisor" light></v-divider>
                <h4 class="mb-4 text-center subtitulo">Die Veranstalter-Lösung</h4>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                  >Die Möglichkeiten von Hoss oder Adam werden um die Veranstalter-Funktionalität erweitert. Ben ist die Lösung für alle Veranstalter. Ob Reisebüro mit Eigenveranstaltung, Spezialveranstalter oder der Neugründer.Ben hilft!</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="mt-5 divisor" :inset="inset"></v-divider>
            <v-card-actions>
              <v-btn class="mx-auto btn_4" text>Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12">
          <v-card
            class="mx-auto"
            max-width="100%"
            raised
            rounded-lg
            style="border: 3px solid #d97c30 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div
                  class="mb-1 text-center encabezado"
                  style="letter-spacing: 6px !important; color: #d97c30 !important; font-family: 'Open Sans' !important; font-weight:700 !important; font-size: 23px !important"
                >AKTUELLES</div>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                    style="color: #d97c30 !important;"
                  >Bis zu 15.000 € Förderung und 80 % Kostenübernahme ! NRW hat ein neues Förderprogramm Mittelstand Innovativ & Digital (MID) konzipiert, welches bis zum 31.12.2020 Gültigkeit hat und für Unternehmen aus NRW vorgesehen ist.</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-card-actions>
              <v-btn class="mx-auto btn_5" text>Mehr erfahren ...</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "features",

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
  border: none;
}

.card_1 {
  max-width: 280;
  min-height: 670;
}

.encabezado {
  font-size: 23px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 700 !important;
}

.contenido {
  line-height: 1.5em !important;
  font-size: 15px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 400 !important;
}
</style>