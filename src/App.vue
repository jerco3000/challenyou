<template>
  <v-app>
    <v-app-bar app color="black" flat>
      <div class="d-flex align-center">
        <v-img
          :src="require('@/assets/challenyou_black_logo3.png')"
          alt="Challenyou Logo"
          contain
          width="200"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn depressed color="error">
        Iniciar sesión
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
//import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",

  components: {},

  data: () => ({
    //
  }),
};
</script>
