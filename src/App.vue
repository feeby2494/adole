<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navigation from './components/Navigation.vue';

</script>

<template>
  <Navigation />
  <div class="container-fluid">
    <div class="row">
      <div class="d-none d-md-block col-md-1 col-lg-2"></div>
      <div class="col-md-10 col-lg-8">
        <RouterView />
      </div>
      <div class="d-none d-md-block col-md-1 col-lg-2"></div>
    </div>
  </div>
</template>

<style>

</style>
