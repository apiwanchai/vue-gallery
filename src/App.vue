<template>
  <v-app>
    <v-app-bar app color="white" dark>
      <v-toolbar-title class="black--text text-h3">Vue</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn to="/">Home</v-btn>
      <v-btn to="/cvview" class="ml-5">Proflie</v-btn>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
    <v-footer padless color="black">
      <v-divider></v-divider>
      <v-col class="text-center" cols="12">
        <v-btn v-for="icon in icons" :key="icon" class="mx-4 white--text" icon>
          <v-icon size="24px" color="grey">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-col>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>
