<template>
<!-- <v-container fluid style="background-color: #cde0e7;"> -->
  <v-footer color="#cde0e7" height="50px" padless>
    <v-row justify="center" no-gutters>
      <v-col class="my-auto text-center" cols="6" style="margin-top: 20px !important;">
        <p class="pie">
          © Bonanza Software GmbH 2018 - {{ new Date().getFullYear() }} | Powered by
          <a
            href="https://itexon.com"
            target="blank"
          >Itexon GmbH</a>
        </p>
      </v-col>
      <v-col class="my-auto text-center"  cols="6">
        <v-btn
          v-for="link in links"
          :key="link"
          color="#d97c30"
          text
          rounded
          class="menu-footer"
          style="padding-left: 4px; padding-right: 4px;"
        >{{ link }}</v-btn>
      </v-col>
    </v-row>
  </v-footer>
<!-- </v-container> -->
</template>


<script>
export default {
  name: "footerpage",

  data: () => ({
    links: ["Kontakt |", "Impressum |", "Datenschutz |", "AGB"],
  }),
};
</script>

<style>
.pie {
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 11px !important;
  font-weight: 400 !important;
  color: #666666 !important;
}

.menu-footer {
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 11px !important;
  font-weight: 400 !important;
  color: #d97c30 !important;
  text-transform: capitalize;
}

.pie a {
  color: #d97c30 !important;
  text-decoration: none;
}

.pie :hover {
  text-decoration: underline;
}

.v-btn :hover {
  text-decoration: underline;
}
</style>