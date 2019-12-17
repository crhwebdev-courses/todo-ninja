<template>
  <div class="team">
    <h1 class="subtitle-1 grey--text">Team</h1>

    <v-container class="my-5">
      <v-row no-gutters>
        <v-col
          cols="12"
          sm="6"
          md="4"
          lg="3"
          v-for="person in team"
          :team="team"
          :key="person.name"
        >
          <v-card flat class="text-center ma-3">
            Hello
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {
  data() {
    return {
      team: [
        { name: "The Net Ninja", role: "Web developer" },
        { name: "Ryu", role: "Graphic designer" },
        { name: "Chun Li", role: "Web developer" },
        { name: "Gouken", role: "Social media maverick" },
        { name: "Yoshi", role: "Sales guru" }
      ]
    };
  }
};
</script>
