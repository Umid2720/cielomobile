<script setup>
import { ref } from 'vue'

const boxes = ref([
    { title: 'What is Conversational Messaging?', text: 'As the name implies, it`s a dialogue. A back and forth with the expectation that when a question is asked, you`ll receive an immediate response. Perhaps it`s better to discuss what it`s not. It is not email. Sure, you can pose a question in an email. But let`s be clear, you are not asking your question, you`re submitting it. And then you wait.' },
    { title: 'The #1 Way to Better Deflect Out of Your IVR', text: 'On average, 10 -15% of the calls in your voice channel are common and repetitive issues that can be better deflected and automated. There are 4 powerful reasons why SMS is the #1 way to better deflect your customers out of the IVR.' },
    { title: 'What is Conversational Messaging?', text: 'During periods of high call volume, frustrated customers abandon the call and head over to the competition. On the other hand, chatbots deployed directly in the call queue automate many low touch requests, reducing customer wait time.' }
])
</script>

<template>
    <div class="industry" data-aos="fade-up" data-aos-delay="10" data-aos-duration="500" data-aos-easing="ease-in-out"
        data-aos-mirror="true" data-aos-once="true" data-aos-anchor-placement="top-center">
        <h2>Industry Insights</h2>
        <div class="container">
            <div class="flex">
                <div class="industry__box" v-for="(box, ind) in boxes" :key="ind">
                    <img :src="'src/assets/industry' + ++ind + '.jpg'" alt="industry">
                    <h4 class="industry__title">{{ box.title }}</h4>
                    <p class="industry__text">{{ box.text }}</p>
                    <a href="" class="read-more">Read More</a>
                </div>
            </div>
        </div>
        <div class="center">
            <a href="" class="industry__btn">More Industry Insights</a>
        </div>
    </div>
</template>

<style>
.industry__btn {
    color: #fff;
    width: 300px;
    font-size: 18px;
    padding: 20px 40px;
    margin-right: 4rem;
    transition: all .5s;
    display: inline-block;
    background-color: #0078E1;
    box-shadow: 0 0 10px 0 rgb(0 0 0 / 50%);
}

.industry__btn:hover {
    transform: scale(1.1);
}

.industry__box {
    width: 30%;
    display: flex;
    padding: 20px 30px;
    flex-direction: column;
    justify-content: center;
    box-shadow: 0 0 10px 0 rgb(0 0 0 / 50%);
}

.industry__box:hover {
    box-shadow: 0 0 10px 5px rgb(0 0 0 / 50%);
}

.industry__box img {
    width: 100%;
}

.industry h4 {
    margin: 1rem 0;
    font-size: 20px;
    line-height: 1.2;
}

.industry p {
    line-height: 30px;
    margin-bottom: 1.5rem;
}

.read-more {
    color: #0067b1;
}

.industry .flex {
    column-gap: 1rem;
}
</style>