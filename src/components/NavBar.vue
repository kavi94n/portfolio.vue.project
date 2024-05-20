<template>
  
    <v-app-bar app color="black" dark flat class="px-12">
      <v-btn>
        <v-icon color="blue" left class="mr-2">fas fa-signature</v-icon>KAVI
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn text @click="scroll('home')" class="text-blue">Home</v-btn>
      <v-btn text @click="scroll('about')" class="text-blue">About</v-btn>
      <v-btn text @click="scroll('portfolio')" class="text-blue">Portfolio</v-btn>
      <v-btn text @click="scroll('Projects')" class="text-blue">Projects</v-btn>
      <v-btn text @click="scroll('contact')" class="text-blue">Contact</v-btn>
    </v-app-bar>
  
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({behavior: "smooth"});
  }
}


}
  
</script>

<style>

</style>