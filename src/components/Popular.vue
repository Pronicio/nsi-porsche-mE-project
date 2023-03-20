<template>
  <section id="popular">
    <h3>Choose Your Electric Car<br>Of The Porsche Brand</h3>
    <div class="container">
      <div class="card" v-for="model in models">
        <h5>{{ model.brand }}</h5>
        <h6>{{ model.model }}</h6>
        <img :src="model.image" :alt="model.model" width="180">
        <div class="features">
          <div class="feature">
            <div class="icon dash-ic"></div>
            <p>3.7 Sec</p>
          </div>
          <div class="feature">
            <div class="icon funds-ic"></div>
            <p>356 Km/h</p>
          </div>
          <div class="feature">
            <div class="icon charg-ic"></div>
            <p>Electric</p>
          </div>
        </div>
        <p class="pricing">{{ model.pricing }}</p>
        <div class="shop">
          <div class="shop-ic"></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const models = [
  {
    brand: "Porsche",
    model: "Turbo S",
    image: "https://i.imgur.com/fojZbzb.png",
    pricing: "$175,900"
  },
  {
    brand: "Porsche",
    model: "Taycan",
    image: "https://i.imgur.com/8t4jYjC.png",
    pricing: "$114,900"
  },
  {
    brand: "Porsche",
    model: "Turbo S Cross",
    image: "https://i.imgur.com/5MdJpdl.png",
    pricing: "$175,900"
  }
]
</script>

<style scoped lang="scss">
@import '../assets/style/components/popular.scss';
</style>
