<template>
  <div class="home">
    <h1>Homepage.</h1>

    <v-btn class="pink white--text">click me</v-btn>
    <v-btn depressed color="pink">click me</v-btn>
    <v-btn text color="pink">click me</v-btn>
    
    <v-btn depressed class="pink white--text">
      <v-icon left>mdi-email</v-icon>
      <span>email me</span>
    </v-btn>

    <v-btn depressed small class="pink white--text">
      <v-icon small left>mdi-email</v-icon>
      <span>email me</span>
    </v-btn>

    <v-btn depressed large class="pink white--text">
      <span>email me</span>
      <v-icon large right>mdi-email</v-icon>
    </v-btn>

    <v-btn depresser fab small dark color="purple" >
      <v-icon>mdi-heart</v-icon>
    </v-btn>

  </div>
</template>

<script>
export default {
  
}
</script>

