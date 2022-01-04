<template>
  <v-app id="main">
    <v-container class="mt-2">
      <v-row justify="center">
        <v-col cols="12" style="z-index: 5" class="pb-0" align="center">
          <v-img
            lazy-src="./assets/dailybear_text.png"
            max-width="400"
            max-height="70"
            src="./assets/dailybear_text.png"
          ></v-img>
        </v-col>
        <v-col
          style="width: 500px; position: absolute"
          class="pt-2"
          align="left"
        >
          <v-img
            lazy-src="./assets/dailybear_left_img.png"
            max-width="116"
            max-height="80"
            src="./assets/dailybear_left_img.png"
          ></v-img>
        </v-col>
        <v-col
          style="width: 500px; position: absolute"
          class="mt-2"
          align="right"
        >
          <v-img
            lazy-src="./assets/dailybear_right_img.png"
            max-width="50"
            max-height="57"
            src="./assets/dailybear_right_img.png"
          ></v-img>
        </v-col>
      </v-row>
    </v-container>
    <v-main>
      <Intro />
      <div style="height: 100px" />
    </v-main>
    <v-footer fixed padless>
      <v-card flat tile width="100%" class="yellow lighten-5 text-center">
        <v-card-text class="grey--text text-overline">
          {{ new Date().getFullYear() }} -
          <strong>Daily Bear</strong>
        </v-card-text>
      </v-card>
    </v-footer>
  </v-app>
</template>

<script>
import Intro from "./components/Intro";

export default {
  name: "App",

  components: {
    Intro,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
#main {
  background-image: url("./assets/background.png");
  background-size: cover;
}
</style>
