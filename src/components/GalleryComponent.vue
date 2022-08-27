<template>
  <div class="px-16 mt-5">
    <Photoswipe>
      <h1 class="text-center mb-5">Gallery Page</h1>
      <v-row>
        <v-col
          cols="12"
          xs="12"
          sm="6"
          md="3"
          v-for="(src, index) in imageList"
          :key="index"
        >
          <img :src="src" v-pswp="src" class="res gallery" height="150px" />
        </v-col>
      </v-row>
    </Photoswipe>
  </div>
</template>
<script>
export default {
  name: "GalleryComponent",
  data() {
    return {
      imageList: [
        require("../assets/img/fruit-01.jpg"),
        require("../assets/img/fruit-02.jpg"),
        require("../assets/img/fruit-03.jpg"),
        require("../assets/img/fruit-04.jpg"),
        require("../assets/img/fruit-05.jpg"),
        require("../assets/img/fruit-06.jpg"),
        require("../assets/img/fruit-07.jpg"),
        require("../assets/img/fruit-08.jpg"),
        require("../assets/img/fruit-09.jpg"),
        require("../assets/img/fruit-10.jpg"),
        require("../assets/img/fruit-11.jpg"),
        require("../assets/img/fruit-12.jpg"),
      ],
    };
  },
  methods: {},
};
</script>
<style lang="scss">
.res {
  width: 100%;
  max-width: 400px;
  height: auto;
  height: 200px;
}
.gallery:hover {
  transform: scale(1.02) perspective(0px);
  box-shadow: 0 10px 10px grey;
}
</style>
