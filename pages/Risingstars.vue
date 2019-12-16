<template>
  <v-content class="py-12">
    <div>
      <v-container>
        <v-row>
          <v-col
            md="8"
            offset-md="2"
            sm="10"
            offset-sm="1"
            xs="10"
            offset-xs="1"
            class="pa-3"
          >
            <h1 class="black--text">
              Varför vill jag bli en rising star?
            </h1>
          </v-col>
        </v-row>
        <v-row>
          <v-col
            md="8"
            offset-md="2"
            sm="10"
            offset-sm="1"
            xs="10"
            offset-xs="1"
            class="pa-3"
          >
            <p class="black--text">
              Som ny inom konsultbranschen har jag mycket att lära mig och jag
              tror att detta program kommer ge mig rätt verktyg för att starta
              min resa på B3. Jag ser fram emot att få en mentor som kan hjälpa
              och stötta mig på vägen. Utöver det tror jag att kunskapsutbytet
              mellan deltagarna i programmet kommer vara otroligt lärorikt och
              jag ser fram emot att få möjlighet att skapa ett större kontaktnät
              inom företaget.
            </p>
          </v-col>
        </v-row>
        <v-row>
          <v-col
            md="8"
            offset-md="2"
            sm="10"
            offset-sm="1"
            xs="10"
            offset-xs="1"
            class="pa-3 text-center"
          >
          <v-responsive>
            <v-img
              class="image"
              :src="require('../assets/img/star.jpg')"
            ></v-img>
          </v-responsive>
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
      title: "Rising Stars"
    };
  }
};
</script>

<style lang="css">
@import "../assets/style.css";
</style>
