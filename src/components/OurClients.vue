<script setup>
import { ref } from 'vue'
import '@splidejs/vue-splide/css';
import { Splide, SplideSlide } from '@splidejs/vue-splide';
const images = ref(['dyson', 'ford', 'mcdonals', 'tyson', 'rbc', 'merck', 'ppd', 'johnson', 'eye'])
</script>

<template>
    <div class="our-clients" data-aos="fade-up" data-aos-delay="10" data-aos-duration="500"
        data-aos-easing="ease-in-out" data-aos-mirror="true" data-aos-once="true"
        data-aos-anchor-placement="top-center">
        <h2>Our Clients</h2>
        <div class="container">
            <Splide
                :options="{ rewind: true, width: '100%', rewindSpeed: 1000, perPage: 4, perMove: 1, gap: '1rem', arrows: false, type: 'loop', pagination: false }">
                <SplideSlide v-for="(image, id) in images" :key="id">
                    <img :src="'src/assets/' + image + '.png'" :alt="image">
                </SplideSlide>
            </Splide>
        </div>
    </div>
</template>

<style>
.our-clients {
    margin: 5rem 0 1rem;
}

.our-clients .container {
    margin: 0 auto;
    max-width: 1140px;
    border-bottom: 3px solid #000;
}
</style>