<template>
  <div class="navBar-container">
    <div class="Center">
      <router-link class="menu" to="/">Home</router-link>
      <router-link class="menu" to="/about">About</router-link>
      <img src="../assets/Logo.png" />
      <router-link class="menu" to="/Project">Project</router-link>
      <router-link class="menu" to="/Contact">Contact</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<style scoped>
.Center {
  display: flex;
  flex-direction: row;
  height: 12vh;
  justify-content: center;
  align-items: center;
  background: #494949;
}
a {
  text-decoration: none;
  color: white;
}

.menu {
  padding: 25px;
  font-size: 25px;
  font-family: "Montserrat", sans-serif;
}

img {
  height: 10vh;
  width: auto;
}
</style>
