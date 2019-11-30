<template>
  <nav>
    <v-app-bar flat app>
      <v-app-bar-nav-icon
        class="grey--text"
        @click.stop="drawer = !drawer"
      ></v-app-bar-nav-icon>
      <v-toolbar-title class="text-uppercase grey--text">
        <span class="font-weight-light">Todo</span>
        <span>Ninja</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn text color="grey">
        <span>Sign Out</span>
        <v-icon right>mdi-logout-variant</v-icon>
      </v-btn>
    </v-app-bar>

    <v-navigation-drawer app v-model="drawer" class="primary">
      <p>test</p>
    </v-navigation-drawer>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      drawer: false
    };
  }
};
</script>
