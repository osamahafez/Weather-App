<template>
      <v-app>
        <v-content>
          <v-toolbar>
            <v-toolbar-title>Weather App</v-toolbar-title>

            <v-spacer></v-spacer>

            <v-toolbar-items>
              <v-btn text> <nuxt-link to="/" class="navbar-link">Home</nuxt-link> </v-btn>
              <v-btn text>Link 2</v-btn>
              <v-btn text>Link 3</v-btn>
            </v-toolbar-items>
          </v-toolbar>

          <!-- content -->
          <nuxt />
        </v-content>
      </v-app>
</template>

<script>
export default {

}
</script>

<style>
  .navbar-link {
    text-decoration: none;
    color: white;
  }
</style>