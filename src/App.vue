<template>
    <Header />
    <Main />
    <Process />
    <Projects />
    <Team />
    <Comments />
    <Contact />
    <Footer />
</template>

<style lang="scss" scoped>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}
</style>

<script setup>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Process from "./components/Process.vue";
import Projects from "./components/Projects.vue";
import Team from "./components/Team.vue";
import Comments from "./components/Comments.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
</script>

<!-- ANOTHER HOMEWORK -->
<!-- <template>
    <div class="main">
        <header class="header1">header</header>
        <nav>nav</nav>
        <figure class="figure1">figure</figure>
        <figure class="figure1">figure</figure>
        <figure class="figure1">figure</figure>
        <header class="header2">header</header>
        <article>article</article>
        <footer class="footer1">footer</footer>
        <header class="header2">header</header>
        <article>article</article>
        <footer class="footer1">footer</footer>
        <header class="header2">header</header>
        <article>article</article>
        <footer class="footer1">footer</footer>
        <footer class="footer2">footer</footer>
    </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Oswald&family=Vollkorn&display=swap");

.main {
    width: auto;
    margin: 300px;
    color: white;
    font-family: "Montserrat", sans-serif;
}
.header1 {
    width: 455px;
    background-color: rgb(21, 179, 137);
    margin: 10px;
    font-size: 28px;
    text-align: center;
    padding: 18px;
}

nav {
    width: 250px;
    background-color: rgba(226, 75, 30, 0.901);
    margin: 10px;
    font-size: 30px;
    text-align: center;
    padding: 18px;
    transform: rotate(-90deg);
    margin-top: 115px;
    position: relative;
    right: 105px;
}

.figure1 {
    width: 70px;
    background-color: rgba(6, 150, 25, 0.861);
    margin: 10px;
    font-size: 20px;
    padding-top: 32.5px;
    padding-bottom: 32.5px;
    padding-left: 25px;
    left: 85px;
    position: relative;
    bottom: 188px;
}

.header2 {
    width: 300px;
    height: 22px;
    padding-top: 3px;
    background-color: rgb(68, 51, 179);
    font-size: 15px;
    text-align: center;
    position: relative;
    bottom: 481px;
    left: 200px;
    margin-top: 10px;
}
article {
    width: 288px;
    background-color: rgb(20, 164, 169);
    font-size: 20px;
    text-align: center;
    padding: 6px;
    position: relative;
    bottom: 481px;
    left: 200px;
}
.footer1 {
    width: 300px;
    height: 22px;
    padding-top: 3px;
    background-color: rgb(200, 26, 55);
    font-size: 15px;
    text-align: center;
    position: relative;
    bottom: 481px;
    left: 200px;
}

.footer2 {
    width: 455px;
    background-color: rgba(181, 12, 215, 0.871);
    margin: 10px;
    font-size: 28px;
    text-align: center;
    padding: 18px;
    position: relative;
    bottom: 480px;
}
</style> -->
