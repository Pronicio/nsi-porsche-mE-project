<template>
  <Header></Header>
  <main>
    <Home></Home>
    <About></About>
  </main>
</template>

<script setup>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About from "./components/About.vue";
</script>

<style lang="scss">
@import './assets/style/style.scss';
</style>
