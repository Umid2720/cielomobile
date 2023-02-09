<template>
    <div class="contact">
        <h2 class="contact__title">Contact Center Innovation</h2>
        <div class="flex between items-center wrapper">
            <p>Get the White Paper which highlights leaders in contact center excellence. Learn how these innovators
                ensure the most profitable, high touch conversations reach live agents; directing low touch routine
                issues immediately to intelligent automated bots – directly in their call queues.</p>
            <a href="" class="download">Download the White Paper</a>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style>
.contact {
    color: #fff;
    display: flex;
    min-height: 440px;
    margin-bottom: 5rem;
    flex-direction: column;
    background-size: cover;
    justify-content: center;
    background-position: center;
    background-repeat: no-repeat;
    background-image: url('../assets/bg-img.jpeg');
}

.wrapper {
    column-gap: 2rem;
    margin: 1rem auto 0;
}

.contact h2 {
    color: #fff;
    margin-left: 10%;
    text-align-last: left;
}

.contact p {
    font-size: 16px;
    max-width: 730px;
    line-height: 1.5;
}

.contact .download {
    padding: 20px;
    font-size: 18px;
    border-radius: 5px;
    transition: all .5s;
    background-color: #5cb85c;
}

.contact .download:hover {
    transform: scale(1.1);
}
</style>