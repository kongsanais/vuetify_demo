<template>
  <v-app>
    <v-app-bar app color="primary" dark>

      <div @click="$router.push('/')"  class="d-flex align-center">
        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn 
        @click="$router.push('/about')"
        target="_blank"
        text
        outlined
      >
        <span class="mr-2">About</span>
        <v-icon >mdi-open-in-new</v-icon>
      </v-btn>  

  </v-app-bar>
    <v-content>
            <router-view></router-view>
    </v-content>
  </v-app>


</template>

<script>
export default {
  name: "App",
  components: {},
  data: () => ({
    //
  }),

};
</script>
