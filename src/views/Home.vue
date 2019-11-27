<template>
  <div class="home">
    <h1>Homepage</h1>
    <div class="container">
      <v-btn class="pink white--text mr-2">click me</v-btn>
      <v-btn depressed color="pink">click me</v-btn>
      <v-btn text color="pink">click me</v-btn>
      <v-btn depressed class="pink white--text mr-2">
        <v-icon left>mdi-email</v-icon>
        <span>EMAIL ME</span>
      </v-btn>
      <v-btn small depressed class="pink white--text mr-2">
        <v-icon left small>mdi-email</v-icon>
        <span>EMAIL ME</span>
      </v-btn>
      <v-btn large depressed class="pink white--text mr-2">
        <span>EMAIL ME</span>
        <v-icon right large>mdi-email</v-icon>
      </v-btn>
      <v-btn fab small dark color="purple">
        <v-icon small>mdi-heart</v-icon>
      </v-btn>
    </div>
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
