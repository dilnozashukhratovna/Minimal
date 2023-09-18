<template>
    <Header />
    <Main />
    <Process />
    <Projects />
    <Team />
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
</script>
