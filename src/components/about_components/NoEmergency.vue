<script>
import ambulence from "@/assets/pictures/ambulence.jpg";

export default {
    data() {
        return {
            ambulence : ambulence
        }
    }
}
</script>

<template>
    <div class="row mt-3">
      <div class="col-12 my-3">
        <h3 class="text-center text-muted h1">Please Remember, We Only Do Non-Emergency Transportation</h3>
      </div>
      <div class="col-sm-6 ">
        <img 
          :src="ambulence"
          class="img-fluid rounded"  
        />
      </div>
      <div class="col-sm-6 ">
        <ul class="list-group list-group-flush">
          <li class="list-group-item h4">We Provide Non-Emergency Transportation, Please CAll 911 for an Emergency!</li>
          <li class="list-group-item">Hostpitals can offload transportation services to us for non-emergency situations</li>
          <li class="list-group-item">Patients pay very little compared to using an ambulence</li>
          <li class="list-group-item">Some Hostpitals may offer free transportation to patients using our services</li>
          <li class="list-group-item">Both Hostpitals and Patients are free to use us</li>
        </ul>
      </div>
    </div>
</template>