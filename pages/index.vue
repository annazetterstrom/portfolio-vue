<template>
  <v-content class="py-12">
    <div class="white">
      <v-container>
        <v-row>
          <v-col md="8" offset-md="2" sm="10" offset-sm="1" xs="10">
            <h1 class="black--text pb-2">Anna Zetterström</h1>
            <h3 class="black--text pb-2">Frontend-utvecklare</h3>
          </v-col>
        </v-row>
        <v-row>
          <v-col md="8" offset-md="2" sm="10" offset-sm="1" xs="10">
            <!-- <v-avatar size="200" class="p-b10"> -->
            <v-img
              class="pt-10 pb-10 round"
              alt="bild"
              :src="require('../assets/img/anna.jpeg')"
              height="200px"
            ></v-img>
            <!-- </v-avatar> -->
          </v-col>
        </v-row>
        <v-row>
          <v-col md="8" offset-md="2" sm="10" offset-sm="1" xs="10">
            <p class="black--text">
              Jag är en målinriktad och mångsidig frontend-utvecklare med fokus
              på användbarhet och enkelhet. Jag brinner för ordning och reda,
              och det är inte ovanligt att jag dyker ner i ett problem utan att
              komma upp innan det är löst. Både på och utanför fotbollsplanen är
              jag en riktig lagspelare och sätter alltid teamets bästa framför
              mina egna intressen. Av team kollegor får jag höra att jag ofta
              sprider energi och optimism i gruppen, samtidigt som jag inte är
              rädd för att föra fram mina åsikter när det behövs. Jag vill
              alltid lära mig nya saker och tror därför att rising star är ett
              utmärk nästa steg för mig.
            </p>
          </v-col>
        </v-row>
        <v-row> </v-row>
      </v-container>
    </div>
    <div>
      <v-container>
        <v-row>
          <v-col md="8" offset-md="2" sm="10" offset-sm="1" xs="10">
            <h3 class="black--text">Kunskaper</h3>
          </v-col>
        </v-row>
        <v-row class="white">
          <v-col
            xl="2"
            lg="2"
            md="2"
            offset-md="2"
            sm="4"
            offset-sm="1"
            xs="10"
          >
            <h3 class="black--text">IT</h3>
            <ul class="white">
              <li class="black--text">HTML</li>
              <li class="black--text">CSS (SCSS)</li>
              <li class="black--text">Javascript</li>
              <li class="black--text">Vue.js</li>
              <li class="black--text">Contenful</li>
              <li class="black--text">Git</li>
            </ul>
          </v-col>
          <v-col
            xl="2"
            lg="2"
            md="2"
            offset-md="2"
            sm="6"
            offset-sm="1"
            xs="10"
          >
            <h3 class="black--text">Språk</h3>
            <ul>
              <li class="black--text"><strong>Svenska</strong> - Modersmål</li>
              <li class="black--text"><strong>Engelska</strong> - Flytande</li>
            </ul>
          </v-col>
          <v-col
            xl="2"
            lg="2"
            md="3"
            offset-md="2"
            sm="6"
            offset-sm="1"
            xs="10"
          >
            <h3 class="black--text">Annat</h3>
            <ul>
              <li class="black--text">Bageri</li>
              <li class="black--text">Konditori</li>
              <li class="black--text">Makeup Artist</li>
            </ul>
          </v-col>
        </v-row>
    </v-container>
    </div>
  </v-content>
</template>

<script>
export default {
  head() {
    return {
      title: "Anna Zetterström"
    };
  }
};
</script>

<style lang="css">
@import "../assets/style.css";
</style>
