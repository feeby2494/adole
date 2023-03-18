<script>
  import OffCanvas from '../components/OffCanvas.vue';
  import CommentForm from '../components/contact_components/CommentForm.vue';
  import drive from "@/assets/pictures/drive.png";

  export default {
    data() {
        return {
            drive: drive
        }
    }
}
</script>

<template>
  <main class="container-fluid">
    <!-- <div class="row mt-3">
      <div class="d-none d-sm-block col-sm-1 col-md-2"></div>
      <div class="d-block col-sm-10 col-md-8">
        <CommentForm />

      </div>
      <div class="d-none d-sm-block col-sm-1 col-md-2"></div>
    </div> -->
    <div class="row mt-4">
      <div class="col-sm-6 mt-3">
        <img 
          :src="drive" 
          class="img-fluid rounded" 
        />
      </div>
      <div class="col-sm-6 mt-3">
        <ul class="list-group list-group-flush">
          <li class="list-group-item">Mikias Fetene</li>
          <li class="list-group-item"><a href="tel:+14695697138">469-569-7138</a></li>
          <li class="list-group-item"><a href="mailto:abole.mtransportation@gmail.com">abole.mtransportation@gmail.com</a></li>
        </ul>
      </div>
    </div>
  </main>
</template>
