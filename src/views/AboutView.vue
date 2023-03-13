<script>
import DogDrivers from "../components/about_components/DogDrivers.vue";
import CustomerFirst from '../components/about_components/CustomerFirst.vue';
import NoEmergency from '../components/about_components/NoEmergency.vue';

export default {
  components: {
    DogDrivers,
    CustomerFirst,
    NoEmergency
  }
}
</script>


<template>
  <main class="container-fluid">
    <DogDrivers />
    <CustomerFirst />
    <NoEmergency />
  </main>
</template>

<style>

</style>
