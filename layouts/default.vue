<template>
      <v-app>

        <v-app-bar app dark color="#273c75" >
            <v-toolbar-title>Weather App</v-toolbar-title>

            <v-spacer></v-spacer>

            <v-toolbar-items>
              <v-btn text> <nuxt-link to="/" class="navbar-link">Home</nuxt-link> </v-btn>
              <v-btn text>Link 2</v-btn>
              <v-btn text>Link 3</v-btn>
            </v-toolbar-items>
        </v-app-bar>

        <v-content>
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

  .navbar-link:visited {
    color: rgb(40, 192, 212);
  }

</style>