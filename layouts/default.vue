<template>
  <v-app>
    <v-toolbar color="cyan" dark tabs>
      <v-spacer></v-spacer>

      <v-toolbar-title>Johannes Berggren</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-tabs slot="extension" v-model="tab" color="cyan" grow>
        <v-tabs-slider color="orange"></v-tabs-slider>

        <v-tab>
          Music
        </v-tab>

        <v-tab>
          Tech
        </v-tab>

        <v-tab>
          Latest
        </v-tab>

        <v-tab>
          About
        </v-tab>

        <v-tab>
          Contact
        </v-tab>
      </v-tabs>
    </v-toolbar>

    <v-content>
      <v-container>
        <nuxt/>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        tab: 2,
        items: [
          'music', 'tech', '/', 'about', 'contact'
        ]
      }
    },
    watch: {
      tab (val) {
        this.$router.push(this.items[val])
      }
    }
  }
</script>

<style>
  .theme--light.application {
    background: #fff;
  }
</style>
