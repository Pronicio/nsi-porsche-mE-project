<template>
  <section id="sponsors">
    <ul>
      <li v-for="brand in sponsors">
        <img :src="brand.logo" :alt="brand.name" width="50">
      </li>
    </ul>
  </section>
</template>

<script setup>
const sponsors = [
  {
    name: "porsche",
    logo: "https://i.imgur.com/7IECLH9.png"
  },
  {
    name: "audi",
    logo: "https://i.imgur.com/ECGkObG.png"
  },
  {
    name: "tesla",
    logo: "https://i.imgur.com/yEDz0wH.png"
  },
  {
    name: "BMW",
    logo: "https://i.imgur.com/qO9FMhy.png"
  },
  {
    name: "lamborghini",
    logo: "https://i.imgur.com/jozbCd4.png"
  },
  {
    name: "lamborghini",
    logo: "https://i.imgur.com/zjQ1j3Y.png"
  },
]
</script>

<style scoped lang="scss">
@import '../assets/style/components/sponsors.scss';
</style>
