<template>
  <Header></Header>
  <main>
    <Home></Home>
    <About></About>
    <Popular></Popular>
    <Offer></Offer>
    <Sponsors></Sponsors>
  </main>
  <Footer></Footer>
</template>

<script setup>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About from "./components/About.vue";
import Popular from "@/components/Popular.vue";
import Offer from "@/components/Offer.vue";
import Sponsors from "@/components/Sponsors.vue";
import Footer from "@/components/Footer.vue"
</script>

<style lang="scss">
@import './assets/style/style.scss';
</style>
