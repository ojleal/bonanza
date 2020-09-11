<template>
  <v-container class="contenedor"
    fluid
  >
    <v-row class="text-right">
      <v-col cols="12" style="padding-top: 0px; margin-top: -10px">
        <span>
          Wir beraten Sie gern:
          <a href="tel +4922089162645">+49 2208 9162 645</a>
          oder
          <a href="mailto: info@bonanza-software.de">info@bonanza-software.de</a>
        </span>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Phoneinfo",
  data() {
    return {};
  },
};
</script>

<style>
.contenedor {
  height: 30px;
}

.contenedor span {
  background-color: #ffffff; 
  color: #61615f !important;
  font-size: 11px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial, sans-serif !important;
  font-weight: 700 !important;
  text-transform: capitalize !important;
}

.contenedor span a {
  color: #d97c30;
  text-decoration: none;
}

span :hover {
  text-decoration: underline !important;
}
</style>