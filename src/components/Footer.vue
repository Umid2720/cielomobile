<template>
    <footer>
        <div class="container">
            <div class="flex jijijii items-center between">
                <ul>
                    <li>
                        <a href="https://cielomobile.com/who-we-are/">Who is Cielo</a>
                    </li>
                    <li>
                        <a href="https://cielomobile.com/what-makes-cielos-sms-better/">What Makes Us Better</a>
                    </li>
                    <li>
                        <a href="https://cielomobile.com/get-started/">Try Demo</a>
                    </li>
                    <span>© 2023 - Cielo Mobile | All rights reserved</span>
                </ul>
                <ul class="two">
                    <li>CONTACT US:</li>
                    <li>
                        <a href="">833-915-0889</a>
                    </li>
                    <li>
                        <a href="">connect@cielomobile.com</a>
                    </li>
                </ul>
            </div>
        </div>
    </footer>
</template>
<script>
export default {

}
</script>
<style>
footer {
    background-color: #ddddde;
}

footer .container {
    margin: 0 auto;
    max-width: 1200px;
    padding: 2rem 0;
}

footer li {
    font-size: 18px;
    margin-bottom: 10px;
}
footer li a{
    color: #0067b1;
}

.two{
    margin-left: auto;
    text-align: right;
}

.two li:first-child{
    font-weight: bold;
}

ul span{
    display: inline-block;
    margin-top: 2rem;
    font-size: 18px;
}

.jijijii{
    width: 100%;
}
</style>