<script setup>

</script>

<template>
  <nav>
    <div class="nav-icon">
      <img src="../assets/icon.png" alt="Navigation icon">
    </div>

    <div class="nav-links">
      <a href="#">About Us</a>
      <a href="#">Affiliates</a>
      <a href="#">Vendors</a>
      <a href="#">Blog</a>
    </div>

    <div class="nav-links">
      <a href="#">Login</a>
      <a href="#"><button>Create Account</button></a>
    </div>
  </nav>
</template>

<style scoped>
nav {
  width: 97vw;
  height: 100px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-content: center;
  align-self: center;
  position: fixed;
  top: 0px;
  background-color: #fff;
}

.nav-icon img {
  height: 35px;
  width: 155px;
}

.nav-links {
  display: inherit;
  gap: 15px;
  justify-content: center;
  align-items: center;
}

a {
  font-size: 18px;
  font-weight: 600;
  text-decoration: none;
  color: black;
}

button {
  padding: 12px 21px;
  border-radius: 15px;
  font-size: 18px;
  font-weight: 600;
  border: none;
  background-color: #B6FF34;
}
</style>
