<template>
  <div class="container">
    <div class="bg">
      <img class="background" src="../assets/mac-close.jpg" alt />
    </div>
    <div class="box">
      <H1>Winch Corp is an IT consultancy firm based in Hong Kong focused on helping our clients to simplify their IT infrastructure</H1>
      <H2>Our main focus</H2>
      <table>
        <tr>
          <th>
            <i class="far fa-envelope"></i>
            <h3>Mail deployment</h3>
          </th>
          <th>
            <i class="fab fa-cloudversify"></i>
            <h3>Cloud migration</h3>
          </th>
          <th>
            <i class="fas fa-server"></i>
            <h3>server administration</h3>
          </th>
        </tr>
        <tr>
          <th>
            <i class="fas fa-laptop-code"></i>
            <h3>Web Development</h3>
          </th>
          <th>
            <i class="fas fa-memory"></i>
            <h3>Infrastructure upgrade</h3>
          </th>
          <th>
            <i class="fas fa-users"></i>
            <h3>IT Formation</h3>
          </th>
        </tr>
      </table>
    </div>
    <div class="box">
      <H1>We have experience for helping our clients migrating from an offline or on premises infrastructure to a fully cloud ones</H1>
    </div>
    <div class="box">
      <h1>we are here to smoothe the transition and help them have the best experience from it, in</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "home"
};
</script>

<style>
.background {
  height: 80vh;
  width: auto;
}

.container {
  display: flex;
  align-items: center;
  flex-direction: column;
}

.box {
  margin: 25px;
  width: 70vw;
  border-radius: 50px;
  background-color: #343434;
  color: #fed766;
  font-family: "Montserrat", sans-serif;
  display: flex;
  align-items: center;
  flex-direction: column;
}

.box > h1 {
  margin: 50px;
}

h2 {
  font-size: 30px;
  margin: 50px;
}

table {
  width: 100%;
}

table > tr {
  margin: 25px;
}

i {
  font-size: 50px;
}

h3 {
  margin-bottom: 25px;
}

.table {
  padding: 50px;
}
</style>
