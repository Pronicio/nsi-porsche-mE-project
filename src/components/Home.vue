<template>
  <section id="home">
    <h1>Choose The Best Car</h1>
    <h2>Porsche Mission E</h2>
    <div class="label">
      <div class="icon-bolt"></div>
      <h3>Electric car</h3>
    </div>
    <img src="../assets/images/car.png" alt="Porsche Mission E" width="380">
    <div class="start" @click="scrollToAbout">
      <p>Start</p>
    </div>
    <div class="ellipses">
      <div class="first"></div>
      <div class="second"></div>
    </div>
  </section>
</template>

<script setup>
function scrollToAbout() {
  document.getElementById("about").scrollIntoView({behavior: 'smooth'}, true);
}
</script>

<style scoped lang="scss">
@import '../assets/style/components/home.scss';
</style>
