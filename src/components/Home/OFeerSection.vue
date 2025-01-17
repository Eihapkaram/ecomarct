<template>
  <div>
    <div id="offercon">
      <v-slide-group
        class="mx-auto"
        id="slide-group2"
        prev-icon="mdi-arrow"
        next-icon="mdi-arrow"
      >
        <v-slide-group-item id="item2">
          <v-card id="item2">
            <v-card-item>
              <img id="item2-img" src="@/assets/images/playstations.webp" />
            </v-card-item>
          </v-card>
        </v-slide-group-item>
        <v-slide-group-item>
          <v-card id="item2">
            <v-card-item>
              <img id="item2-img" src="@/assets/images/chairs.webp" />
            </v-card-item>
          </v-card>
        </v-slide-group-item>
        <v-slide-group-item>
          <v-card id="item2">
            <v-card-item>
              <img id="item2-img" src="@/assets/images/headset.webp" />
            </v-card-item>
          </v-card>
        </v-slide-group-item>
      </v-slide-group>
    </div>
    <v-container>
      <div id="offer2">
        <img id="img3" src="@/assets/images/iphones.webp" />
        <img id="img4" src="@/assets/images/laptops.webp" />
      </div>
    </v-container>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
#slide-group2 {
  position: relative;
  display: flex;
  justify-content: center;
}
#item2 {
  width: 450px;
  background-color: transparent;
}
#item2-img {
  width: 400px;
}
#item2:hover {
  scale: 1.1;
  transition: all, 2s;
}
#offercon {
  background-color: rgb(243, 237, 237);
}
#img3 {
  width: 600px;
}
#img3:hover {
  scale: 0.9;
  transition: all, 2s;
}
#img4 {
  width: 600px;
}
#img4:hover {
  scale: 0.9;
  transition: all, 2s;
}
#offer2 {
  display: flex;
  justify-content: center;
  gap: 40px;
  position: relative;
}
/*/desktop/*/
@media (max-width: 1366px) {
}
/*/tablet/*/
@media (max-width: 991px) {
  #item2 {
    width: 400px;
    background-color: transparent;
  }
  #item2-img {
    width: 390px;
  }
  #offer2 {
    display: flex;
    justify-content: center;
    gap: 5px;
    position: relative;
  }
  #img3 {
    width: 390px;
  }
  #img4 {
    width: 390px;
  }
}
/*/mobile/*/
@media (max-width: 500px) {
}
</style>
