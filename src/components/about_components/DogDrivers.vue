<script>
import dogDriver from "@/assets/pictures/dog-driver.jpg";

export default {
    data() {
        return {
            dogDriver: dogDriver
        }
    }
}
</script>

<template>
    <div class="row mt-3">
      <div class="col-12 my-3">
        <h3 class="text-center text-muted h1">No Dog Drivers Here!</h3>
      </div>
      <div class="col-sm-6 ">
        <img 
          :src="dogDriver"
          class="img-fluid rounded"  
        />
      </div>
      <div class="col-sm-6 ">
        <ul class="list-group list-group-flush">
          <li class="list-group-item h4">Our Drivers are Professional!</li>
          <li class="list-group-item">Clean Driving Records</li>
          <li class="list-group-item">Professional Service</li>
          <li class="list-group-item">Rating System to keep Accountability</li>
          <li class="list-group-item">Well Maintained Vehicles</li>
        </ul>
      </div>
    </div>
</template>