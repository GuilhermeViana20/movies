<template>
  <HelloWorld />

  <v-bottom-navigation grow>
    <v-btn value="recent">
      <v-icon>mdi-home</v-icon>
      Home
    </v-btn>

    <v-btn value="favorites">
      <v-icon>mdi-heart</v-icon>
      Favoritos
    </v-btn>

    <v-btn value="nearby">
      <v-icon>mdi-account</v-icon>

      Conta
    </v-btn>
  </v-bottom-navigation>
</template>

<script setup>
  import HelloWorld from '@/components/HelloWorld.vue'
</script>
