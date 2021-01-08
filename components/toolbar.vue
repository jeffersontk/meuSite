<template>
  <div class="toolbar-left">
    <IconPopUp />
    <v-card class="overflow-hidden fix-theme-light" light>
      <v-app-bar
        absolute
        color="white"
        class="fix-theme-light"
        elevate-on-scroll
      >
        <v-btn class="fix-v-btn" nuxt to="/">
          <img
            style="margin-left: 10px"
            width="120"
            height="70"
            src="../assets/logo.png"
          />
        </v-btn>

        <v-spacer></v-spacer>

        <v-btn nuxt to="/projects">Projetos</v-btn>

        <v-btn nuxt to="/about">Sobre Min </v-btn>

        <v-btn nuxt to="/contact">Contato</v-btn>
      </v-app-bar>
    </v-card>
  </div>
</template>
<style>
.fix-v-btn::before {
  background-color: transparent;
}
.fix-.theme--light.v-app-bar.v-toolbar.v-sheet {
  background-color: white;
}
</style>
<script>
import IconPopUp from '~/components/iconPopUp.vue'

export default {
  components: {
    IconPopUp,
  },
}
</script>
