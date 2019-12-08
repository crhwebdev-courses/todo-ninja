<template>
  <div class="dashboard">
    <h1 class="subtitle-1 grey--text">Dashboard</h1>

    <v-container class="my-5">
      <v-row>
        <v-col cols="12" md="6">
          <v-btn outlined block color="primary">1</v-btn>
        </v-col>
        <v-col cols="12" md="6">
          <v-btn outlined block color="primary">2</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {};
</script>
<style>
.container {
  display: flex;
  flex-wrap: nowrap;
  justify-content: center;
}
</style>
