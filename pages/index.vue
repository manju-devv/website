<template>
  <div class="main-container">
    <Navbar />
    <HomePage />
    <FeaturesPage />
    <PricePage />
    <TestimonialsPage />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from "~/components/Navbar.vue";
import HomePage from "~/components/HomePage.vue";
import FeaturesPage from "~/components/FeaturesPage.vue";
import PricePage from "~/components/PricePage.vue";
import TestimonialsPage from "~/components/TestimonialsPage.vue";
import Footer from "~/components/Footer.vue";

import { definePageMeta } from "#imports";
definePageMeta({
  title: "Landmark - Home",
  description: "Home page of Landmark website designed using Nuxt3",
});
</script>

<style>
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family:
    system-ui,
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    Roboto,
    Oxygen,
    Ubuntu,
    Cantarell,
    "Open Sans",
    "Helvetica Neue",
    sans-serif;
  overflow-x: hidden;
}

.main-container {
  display: flex;
  flex-direction: column;
  position: relative;
  overflow-x: hidden;
}
</style>
