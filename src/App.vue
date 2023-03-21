<template>
  <Header></Header>
  <main>
    <Home></Home>
    <About></About>
    <Popular></Popular>
    <Offer></Offer>
  </main>
</template>

<script setup>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About from "./components/About.vue";
import Popular from "@/components/Popular.vue";
import Offer from "@/components/Offer.vue";
</script>

<style lang="scss">
@import './assets/style/style.scss';
</style>
