<template>
  <footer>
    <div class="about">
      <div class="logo"></div>
      <p>We offer the best electric cars of<br> the most recognized brands in<br> the world.</p>
    </div>
    <table>
      <tr>
        <th><h4>Company</h4></th>
        <th><h4>Information</h4></th>
        <th><h4>Follow us</h4></th>
      </tr>
      <tr>
        <td>About</td>
        <td>Request a quote</td>
        <td>
          <div class="socials">
            <div class="ic facebook"></div>
            <div class="ic instagram"></div>
            <div class="ic twitter"></div>
          </div>
        </td>
      </tr>
      <tr>
        <td>Cars</td>
        <td>Find a dealer</td>
      </tr>
      <tr>
        <td>History</td>
        <td>Contact us</td>
      </tr>
      <tr>
        <td>Shop</td>
        <td>Services</td>
      </tr>
    </table>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped lang="scss">
@import '../assets/style/components/footer.scss';
</style>

