<template>
    <div class="container">
        <p class="about-title">Hello, this is my blog in which I will tell you about:</p>
        <ul class="about-list-first">
            <li class="list-title">Frontend</li>
            <li>JS</li>
            <li>Vue.js</li>
            <li>Jquery</li>
            <li>CSS</li>
        </ul>
        <ul class="about-list-second">
            <li class="list-title">Backend</li>
            <li>Php</li>
            <li>Laravel</li>
            <li>Symfony</li>
            <li>Python</li>
            <li>Django</li>
            <li>Flask</li>
            <li>Designed patterns</li>
            <li>Different technologies(Sockets, queues...)</li>
        </ul>
        <p class="copyright">&copy; 2019 All rights reserved </p>
    </div>
</template>

<script>
    export default {
        name: "Hello"
    }
</script>

<style scoped>
.container {
    height: 100%;
}

.about-title{
    font-size: 30px;
}

ul li {
    font-size: 22px;
    padding: 4px;
}

.list-title{
    margin-bottom: 18px;
    font-weight: bold;
}

.about-list-first{
    width: 50%;
    float: left;
}

.about-list-second{
    width: 50%;
    float: right;
}

.copyright {
    position: absolute; bottom: 0;
    font-size: 20px;
}
</style>