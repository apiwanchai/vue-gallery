<template>
  <div class="pa-10 grey">
    <v-card width="1400" class="mx-auto">
      <v-row>
        <v-col cols="12" xs="12" sm="12" md="4"  >
          <v-col class="pa-5 d-flex justify-center" cols="12">
            <v-avatar class="profile" color="grey" size="164">
              <v-img src="../assets/img/proflie.jpg"></v-img>
            </v-avatar>
          </v-col>
          <p class="text-center">Apiwanchai Yingtavorn</p>
          <p class="text-center">Nickname: Nex </p>
          <p class="text-center mb-0"> Age: 24</p>
          <v-col cols="12" class="px-10 px-md-5" >
            <p class="primary--text">Skills</p>
            <v-divider></v-divider>
            <v-row class="mt-2 ">
              <v-col cols="12" md="6" sm="6" xs="12">
                <v-icon color="yellow"> mdi-language-javascript </v-icon>
                Javascript
              </v-col>
              <v-col cols="12" md="6" sm="6" xs="12">
                <v-icon color="success"> mdi-vuejs </v-icon>
                Vuejs
              </v-col>
              <v-col cols="12" md="6" sm="6" xs="12">
                <v-icon color="primary"> mdi-vuetify </v-icon>
                vuetify
              </v-col>
              <v-col cols="12" md="6" sm="6" xs="12">
                <v-icon color="orange"> mdi-language-html5 </v-icon>
                HTML
              </v-col>
              <v-col cols="12" md="6" sm="6" xs="12">
                <v-icon color="primary"> mdi-language-css3 </v-icon>
                CSS
              </v-col>
            </v-row>
          </v-col>
          <v-col cols="12" class="px-10 px-md-5">
            <p class="primary--text">Language</p>
            <v-divider></v-divider>
            <p class="mt-3">Thai (Native)</p>
            <p class="mt-2">English (basic)</p>
          </v-col>
          <v-col cols="12 " class="px-10 px-md-5">
            <p class="primary--text">Contact</p>
            <v-divider></v-divider>
            <v-row class="mt-2">
              <v-col>
                <v-icon color="grey" class="mr-2"> mdi-github </v-icon>
                https://github.com/apiwanchai
              </v-col>
              <v-col cols="12">
                <v-icon color="red" class="mr-2"> mdi-gmail </v-icon>
                apwiwanchai1998@gmail.com
              </v-col>
              <v-col cols="12" xs="12">
                <v-icon color="primary" class="mr-2">
                  mdi-phone-outline
                </v-icon>
                094-4189-175
              </v-col>
              <v-col xs="12">
                <v-icon color="success" class="mr-2">
                  mdi-map-marker-outline
                </v-icon>
                98/170 rama 2, soi 69, Khun Thian Bangkok
              </v-col>
            </v-row>
          </v-col>
        </v-col>
        <v-divider vertical  v-show="!$vuetify.breakpoint.smAndDown"></v-divider>
        <v-col cols="12" class=" px-sm-10 px-10  "  sm="12" md="7" xs="12" >
          <p class="primary--text text-h5 ">EXPERIENCE</p>
          <v-divider></v-divider>
          <p class="px-5 mt-5">FULLSTACK DEVELOPER</p>
          <p class="px-5 grey--text">
            Onemoby | 23 norvember 2020 - 16 march 2021 Trainee Fullstack
            developer
          </p>
          <p class="px-5 mt-5">Front-end</p>
          <p class="px-5 grey--text">-Use React React hook and Nextjs</p>
          <p class="px-5 grey--text">
            -Develop website form page and table page
          </p>
          <p class="px-5 mt-5">Back-end</p>
          <p class="px-5 grey--text">-Use Nodejs Nestjs and Mongodb</p>
          <p class="px-5 mt-5">FRONTEND DEVELOPER</p>
          <p class="px-5 grey--text">
            PP_ontime | 1 September 2021 - 30 June 2022
          </p>
          <p class="px-5 mt-5">Front-end</p>
          <p class="px-5 grey--text">-Use Vue Vuetify</p>
          <p class="px-5 grey--text mb-5">
            -Develop website about track work engineer
          </p>
          <p class="primary--text text-h5">Hobby</p>
          <v-divider></v-divider>
          <p class="px-5 mt-5">
            <v-icon class="mr-2">mdi-soccer</v-icon> Football
          </p>
          <p class="px-5">
            <v-icon class="mr-2">mdi-controller</v-icon> Video Game
          </p>
          <p class="px-5"><v-icon class="mr-2">mdi-laptop</v-icon> Coding</p>
        </v-col>
      </v-row>
    </v-card>
  </div>
</template>

<script>
export default {
  name: "VueGalleryCVpage",
};
</script>
