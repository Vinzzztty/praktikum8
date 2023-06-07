<template>
    <Navbar />
    <br />
    <Hero />
    <br />
    <middleBody />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import MiddleBody from "./components/MiddleBody.vue";

export default {
    name: "App",
    components: { Navbar, Hero, MiddleBody },
};
</script>
