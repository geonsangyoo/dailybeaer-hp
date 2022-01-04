<template>
  <v-container>
    <div style="height: 20px"></div>
    <v-row justify="center">
      <v-col cols="12" align="center">
        <v-btn
          class="mx-2"
          fab
          small
          color="brown darken-2"
          href="mailto:dailybear.qna@google.com"
          target="_blank"
        >
          <v-icon color="white"> mdi-email </v-icon>
        </v-btn>
        <v-btn
          class="mx-2"
          fab
          small
          color="brown darken-2"
          href="https://github.com/geonsangyoo/dailybear"
          target="_blank"
        >
          <v-icon color="white"> mdi-github </v-icon>
        </v-btn>
      </v-col>
    </v-row>
    <v-row justify="center">
      <v-col cols="12">
        <p class="my-2 text-h4 font-weight-thin text-center">
          <span>Pick your bear every day!</span>
        </p>
        <div style="height: 10px"></div>
        <v-img
          :src="require('../assets/screenshot65_1.png')"
          class="my-3"
          contain
          height="800"
        />
      </v-col>
      <div style="height: 30px"></div>
      <v-col cols="12">
        <p class="my-2 text-h4 font-weight-thin text-center">
          <span>Write your own story every day!</span>
        </p>
        <div style="height: 10px"></div>
        <v-img
          :src="require('../assets/screenshot65_2.png')"
          class="my-3"
          contain
          height="800"
        />
      </v-col>
      <div style="height: 30px"></div>
      <v-col cols="12">
        <p class="my-2 text-h4 font-weight-thin text-center">
          <span>Check out your statistic view of bear every month!</span>
        </p>
        <div style="height: 10px"></div>
        <v-img
          :src="require('../assets/screenshot65_3.png')"
          class="my-3"
          contain
          height="800"
        />
      </v-col>
      <div style="height: 30px"></div>
      <v-col cols="12">
        <p class="my-2 text-h4 font-weight-thin text-center">
          <span>The List view with your story & bear get ready!</span>
        </p>
        <div style="height: 10px"></div>
        <v-img
          :src="require('../assets/screenshot65_4.png')"
          class="my-3"
          contain
          height="800"
        />
      </v-col>
      <div style="height: 30px"></div>
      <v-col cols="12">
        <p class="my-2 text-h4 font-weight-thin text-center">
          <span>The List view with your story & bear get ready!</span>
        </p>
        <div style="height: 10px"></div>
        <v-img
          :src="require('../assets/screenshot65_4.png')"
          class="my-3"
          contain
          height="800"
        />
      </v-col>
      <div style="height: 30px"></div>
      <v-col cols="12">
        <p class="my-2 text-h4 font-weight-thin text-center">
          <span>Change your font!</span>
        </p>
        <div style="height: 10px"></div>
        <v-img
          :src="require('../assets/screenshot65_5.png')"
          class="my-3"
          contain
          height="800"
        />
      </v-col>
      <div style="height: 30px"></div>
      <v-col cols="12">
        <p class="my-2 text-h4 font-weight-thin text-center">
          <span>Share your story!</span>
        </p>
        <div style="height: 10px"></div>
        <v-img
          :src="require('../assets/screenshot65_6.png')"
          class="my-3"
          contain
          height="800"
        />
      </v-col>
      <div style="height: 30px"></div>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "intro",

  data: () => ({}),
};
</script>

<style scoped>
span {
  border-bottom: 3px solid #ffff58;
  box-shadow: inset 0 -18px 0 #ffff58;
}
</style>
