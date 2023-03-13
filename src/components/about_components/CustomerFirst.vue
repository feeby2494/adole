<script>
import wheelchairFreedom from "@/assets/pictures/wheelchair-freedom.jpg";

export default {
    data() {
        return {
            wheelchairFreedom : wheelchairFreedom
        }
    }
}
</script>

<template>
    <div class="row mt-3">
      <div class="col-12 my-3">
        <h3 class="text-center text-muted h1">We Are Here For You</h3>
      </div>
      <div class="col-sm-6 ">
        <ul class="list-group list-group-flush">
          <li class="list-group-item h4">We Do this to Help Patients, Doctors, and Hostpitals Alike!</li>
          <li class="list-group-item">Don't let life hold you back and get the care you deserve</li>
          <li class="list-group-item">Hostpitals can off load transportation to us</li>
          <li class="list-group-item">Patients can not worry about missing appointemnts anymore</li>
          <li class="list-group-item">The Burden of Transportation is our Issue Now</li>
        </ul>
      </div>
      <div class="col-sm-6 ">
        <img 
          :src="wheelchairFreedom"
          class="img-fluid rounded"  
        />
      </div>
    </div>
</template>