<template>
    <div class="our-clients">
        <h2>Our Clients</h2>
        <div class="container">
            <Splide
                :options="{ rewind: true, width: '100%', rewindSpeed: 1000, perPage: 4, perMove: 1, gap: '1rem', arrows: false, type: 'loop', pagination: false }">
                <SplideSlide>
                    <img src="../assets/dyson.png" alt="dyson">
                </SplideSlide>
                <SplideSlide>
                    <img src="../assets/ford.png" alt="ford">
                </SplideSlide>
                <SplideSlide>
                    <img src="../assets/mcdonals.png" alt="mcdonals">
                </SplideSlide>
                <SplideSlide>
                    <img src="../assets/merck.png" alt="merck">
                </SplideSlide>
                <SplideSlide>
                    <img src="../assets/johnson.png" alt="johnson">
                </SplideSlide>
                <SplideSlide>
                    <img src="../assets/eye.png" alt="eye">
                </SplideSlide>
                <SplideSlide>
                    <img src="../assets/ppd.png" alt="ppd">
                </SplideSlide>
                <SplideSlide>
                    <img src="../assets/rbc.png" alt="rbc">
                </SplideSlide>
                <SplideSlide>
                    <img src="../assets/tyson.png" alt="tyson">
                </SplideSlide>
            </Splide>
        </div>
    </div>
</template>
<script>
import '@splidejs/vue-splide/css';
import { Splide, SplideSlide } from '@splidejs/vue-splide';
export default {
    components: {
        Splide,
        SplideSlide,
    },
}
</script>
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