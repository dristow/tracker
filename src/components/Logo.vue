<template>
    <v-container fluid>
      <v-slide-y-transition mode="out-in">
        <v-layout column align-center>
          <v-card-media height="80" src="../assets/logo.png"></v-card-media>
        </v-layout>
      </v-slide-y-transition>
    </v-container>
  </template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'LogoImg'
})
</script>