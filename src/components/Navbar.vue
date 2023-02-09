<template>
    <nav class="navbar">
        <div class="container">
            <div class="logo">
                <img src="../assets/logo.png" alt="logo" width="41" class="logo">
            </div>
            <ul class="menu__list">
                <li class="menu__item">
                    <router-link class="menu__link" to="#">Our Technology</router-link>
                </li>
                <li class="menu__item">
                    <router-link class="menu__link" to="#">Applications</router-link>
                </li>
                <li class="menu__item">
                    <router-link class="menu__link" to="#">Clients</router-link>
                </li>
                <li class="menu__item">
                    <router-link class="menu__link" to="#">Try Demo</router-link>
                </li>
                <li class="menu__item">
                    <a class="menu__link" href="tel:+6177848837">Call or Text: 617-784-8837</a>
                </li>
            </ul>
        </div>
    </nav>
</template>
<script>
export default {

}
</script>
<style lang="css">
.navbar {
    background-color: #efefef;
}

.container {
    display: flex;
    width: 1200px;
    margin: 0 auto;
    padding: 13px 20px;
    align-items: center;
    justify-content: space-between;
}

.menu__list {
    display: flex;
    column-gap: 30px;
}

.menu__item {
    padding-top: 15px;
    padding-bottom: 15px;
}

.menu__link {
    color: #004ec3;
    font-size: 16px;
}
</style>