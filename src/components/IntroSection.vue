<template>
    <div class="intro-section">
        <h1>
            Be impactful. <br>
            Voice channel technology that <br>
            actually makes a difference.
        </h1>

        <div class="intro-section__btns">
            <a href="#" class="download__btn">Download Trial</a>
            <a href="#" class="demo__btn">Schedule a Demo</a>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style lang="css">
.intro-section {
    height: 800px;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-image: url('../assets/bg-image.png');
    display: flex;
    flex-direction: column;
    justify-content: center;
    position: relative;
}

.intro-section h1 {
    color: #0078e1;
    font-size: 56px;
    text-align: center;
    text-shadow: 0 0 5px #fff;
}

.intro-section__btns{
    bottom: 5rem;
    left: 3rem;
    position: absolute;
}

.intro-section__btns a{
    padding: 20px 43px;
    background-color: #5cb85c;
    box-shadow: 0 0 10px 0 rgb(0 0 0 / 50%);
    font-size: 18px;
    border-radius: 5px;
    color: #fff;
}
.download__btn{
    margin-right: 16px;
}
</style>