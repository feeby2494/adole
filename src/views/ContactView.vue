<script setup>
  import OffCanvas from '../components/OffCanvas.vue';
  import CommentForm from '../components/contact_components/CommentForm.vue';
</script>

<template>
  <main class="container-fluid">
    <div class="row mt-3">
      <div class="d-none d-sm-block col-sm-1 col-md-2"></div>
      <div class="d-block col-sm-10 col-md-8">
        <CommentForm />
      </div>
      <div class="d-none d-sm-block col-sm-1 col-md-2"></div>
    </div>
  </main>
</template>
