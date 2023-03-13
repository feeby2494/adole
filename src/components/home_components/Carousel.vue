<script>
import driver from "@/assets/pictures/driver.jpg";
import doctorVisit from "@/assets/pictures/doctor-visit.jpg";
import happyCustomer from "@/assets/pictures/happy-customer.jpg";

export default {
    data() {
        return {
            driver: driver,
            doctorVisit: doctorVisit,
            happyCustomer: happyCustomer
        }
    }
}
</script>

<template>
    <div id="carouselExample" class="carousel slide carousel-fade" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img :src="driver" class="d-block w-100" alt="our professional driver"> 
            </div>
            <div class="carousel-item">
                <img :src="doctorVisit" class="d-block w-100" alt="doctor consultation"> 
            </div>
            <div class="carousel-item">
                <img :src="happyCustomer" class="d-block w-100" alt="happy customer"> 
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>