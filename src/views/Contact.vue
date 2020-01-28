<template>
  <div class="container">
    <img class="bg" src="../assets/contact-bg.png" />
    <div class="box">
      <H1>Winch Corp</H1>
      <H2>We would be more than happy to discuss your project</H2>
      <div class="text">
        <i class="fab fa-whatsapp">
          <a href="https://wa.me/85296545784" target="_blank">Click for chatting by Whatsapp</a>
        </i>
        <i class="far fa-envelope">
          <a href="mailto:contact@winch-corp.com">Click here for sending us an email</a>
        </i>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  align-items: center;
  flex-direction: column;
}

.bg {
  width: 100vw;
  height: 50vh;
}

.box {
  background-color: #343434;
  width: 80vw;
  height: 100vh;
}

h1 {
  padding-top: 25px;
}

.text a {
  color: white;
  text-decoration: none;
  font-size: 25px;
  font-family: "Montserrat", sans-serif;
  padding-left: 20px;
}

.text {
  display: flex;
  flex-direction: column;
}

h1,
h2,
i {
  color: #fed766;
}

i {
  font-size: 50px;
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
