<template>
  <div>
    <app-header />
    <nuxt />
  </div>
</template>

<script lang="ts">
import appHeader from '../components/header.vue'
export default {
  components: { appHeader }
}
</script>

<style>
body {
  margin: 0 !important;
}
</style>
