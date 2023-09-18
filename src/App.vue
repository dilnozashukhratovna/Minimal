<template>
    <Header />
    <Main />
    <Process />
    <Projects />
    <Team />
    <Comments />
    <Contact />
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
</script>
