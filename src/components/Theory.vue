<template>
  <v-container fluid style="background-color: #cde0e7; border-bottom: 2px solid white">
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto mt-5 align-items-center"
      style="background-color: #cde0e7;"
    >
      <v-row>
        <v-col cols="4">
          <v-card class="mx-auto card_1" max-width="380" min-height="380" raised rounded-lg>
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div
                  class="mb-1 text-center encabezado"
                  style="color: #d97c30 !important"
                >Wir nix Theorie, wir Praxis</div>
                <v-divider class="pt-2 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon color="#d97c30">fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon color="#d97c30">fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <v-divider class="pt-2 divisor" light></v-divider>
                <div class="mx-auto text-center">
                  <p
                    class="contenido"
                  >Bei uns profitieren Sie von unseren "gelebten" Erfahrungen. Wir erklommen viele Gipfel aber schrammten auch am machen Abgrund entlang.</p>
                  <p class="contenido">Auf unseren Wegen trafen wir viele "Theoretiker"</p>
                  <p
                    class="contenido"
                  >Danach wussten wir immer "Hands-on" Erfahrungen sind durch nichts zu ersetzen.</p>
                </div>
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col cols="4">
          <v-card class="mx-auto card_1" max-width="380" min-height="380" raised rounded-lg>
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div
                  class="mb-1 text-center encabezado"
                  style="color: #d97c30 !important"
                >Alles aus einer Hand</div>
                <v-divider class="pt-2 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon color="#d97c30">fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon color="#d97c30">fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <v-divider class="pt-2 divisor" light></v-divider>
                <div class="mx-auto text-center">
                  <p class="contenido">Viele Köche verderben den Brei…</p>
                  <p
                    class="contenido"
                  >Kein Kompetenz Gerangel, kein Verantwortungswirrwarr, keine Reibungsverluste, keine Stille Post und kein Fingerpointing.</p>
                  <p
                    class="contenido"
                  >Wir bieten Bruchfreie Konzepte und Lösungen über die vier im folgenden genannten Bereiche.</p>
                </div>
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col cols="4">
          <v-card class="mx-auto card_1" max-width="380" min-height="380" raised rounded-lg>
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div
                  class="mb-1 text-center encabezado"
                  style="color: #d97c30 !important"
                >Techniken von Morgen</div>
                <v-divider class="pt-2 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon color="#d97c30">fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon color="#d97c30">fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <v-divider class="pt-2 divisor" light></v-divider>
                <div class="mx-auto text-center">
                  <p
                    class="contenido"
                  >Sie sehen sich mit immer neuen Anforderungen, immer kürzeren Produktzyklen und komplexeren Kundenwünschen konfrontiert. Die Technik und die Vertriebsmöglichkeiten schreiten immer schneller voran. Auch der Wettbewerbsdruck steigt. Wir sind ein vitaler Partner.</p>
                  <p
                    class="contenido"
                  >Daher brauchen Sie einen starken und zuverlässigen Partner mit Lösungen auf der Höhe der Zeit!</p>
                </div>
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "theory",

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

.contenido {
  line-height: 1.5em !important;
  font-size: 15px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 400 !important;
}
</style>