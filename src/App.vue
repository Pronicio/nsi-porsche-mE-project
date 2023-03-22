<template>
  <Header></Header>
  <main>
    <router-view/>
  </main>
  <Footer></Footer>
</template>

<script setup>
import Header from './components/Header.vue'
import Footer from "@/components/Footer.vue"
</script>

<style lang="scss">
@import './assets/style/style.scss';
</style>
