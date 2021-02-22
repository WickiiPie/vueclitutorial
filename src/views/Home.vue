<!--
<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>
-->

<template>
  <div class="home">
  <h1> Home page </h1>
  <p class="red yellow--text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse nemo nam mollitia vel in, quidem itaque, perspiciatis est, accusantium qui quo enim ipsa tempore exercitationem maxime expedita sequi iste voluptas?</p>
  <p class="pink lighten-red--text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae, nobis. Necessitatibus nihil velit deleniti iusto in vero esse architecto officiis? Nobis laudantium sunt corrupti similique et dignissimos incidunt dolore dolor?</p>
  <p class="pink lighten red--text text--darken-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae, nobis. Necessitatibus nihil velit deleniti iusto in vero esse architecto officiis? Nobis laudantium sunt corrupti similique et dignissimos incidunt dolore dolor?</p>
  <h1 class="display-4">Massive display</h1>
  <p class="headline">this is a heading</p>
  <p class="subheading font-weight-bold">this is a subheading</p>
  <!-- buttons -->
  <v-btn>click me</v-btn>
  <v-btn dark color="pink">pink button</v-btn>
  <!-- no shadow button is depressed -->
  <v-btn depressed dark color="pink">pink button</v-btn>
  <!-- flat color controls text color and hover color -->
  <v-btn flat color="pink">pink button</v-btn>


  <br>
  <v-btn depressed class="pink white--text">
    <!-- go to material design icons to learn -->
    <v-icon left>mdi-email</v-icon>
    <span>email me</span>
  </v-btn>
  <v-btn depressed large class="yellow black--text">
    <!-- go to material design icons to learn -->
    <v-icon left>mdi-email</v-icon>
    <span>dm me</span>
  </v-btn>

  </div>
  </template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  // name: 'Home',
  // components: {
  //   HelloWorld
  // }
}
</script>
