<template>
  <div>
    <Navbar />
    <Home />
    <About />
    <Background />
  </div>
</template>

<script setup>
import Navbar from "./components/Navbar.vue";
import Home from "./views/HomeView.vue";
import About from "./views/AboutView.vue";
import Background from "./views/BackgroundView.vue";
</script>
