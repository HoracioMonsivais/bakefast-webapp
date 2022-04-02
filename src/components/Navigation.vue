<template>
  <nav class="nav" >
    <router-link to="/">
      <figure class="nav__logo">
        <img class="nav_bakefast" src="../assets/Icons/bakefast_logo.svg" alt="">
      </figure>
    </router-link>
    <router-link to="/checkout">
       <figure class="nav__checkout">
        <img class="nav_kart" src="../assets/Icons/CheckoutKart.svg" alt="">
      </figure>
    </router-link>
  </nav>
  <router-view/>
</template>

<script>
export default {
  name: 'Navigation',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

nav {
  padding: 20px 60px;
  background-color: #fff;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

</style>
