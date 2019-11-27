<template>
  <div class="home">
    <h1>Homepage</h1>
    <v-btn class="hidden-md-and-down">click me</v-btn>
    <v-btn dark color="pink" class="hidden-md-and-up">click me</v-btn>
    <v-btn dark color="blue" class="hidden-sm-only">click me</v-btn>
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
