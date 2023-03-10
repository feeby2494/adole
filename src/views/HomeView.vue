<template>
  <main class="container-fluid">
    <div class="row">
      <div class="col-12 my-3">
        <HeroSection />   
      </div>
    </div> 
    <div class="row">
      <div class="col-12 mt-3">
        <Carousel />
      </div>
    </div>
    <div class="row">
      <div class="col-sm-6 mt-3">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <OffCanvas />
          </div>
        </div>
      </div>
      <div class="col-sm-6 mt-3">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <OffCanvas />
          </div>
        </div>
      </div>  
    </div> 
  </main>
</template>

<script>
  import OffCanvas from '../components/OffCanvas.vue';
  import Carousel from '../components/home_components/Carousel.vue';
  import CardInfo from '../components/home_components/CardInfo.vue';
  import HeroSection from '../components/home_components/HeroSection.vue'

  export default {  
    components: {
    OffCanvas,
    Carousel,
    CardInfo,
    HeroSection
    
}
  }
</script>