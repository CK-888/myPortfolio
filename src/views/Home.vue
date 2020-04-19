<template>
  <section class="home">
    <div class="first">
      <!-- <img src="../assets/homeshot.jpg" alt="homeshot" /> -->
      <h1>Welcome My Portfolio</h1>
      <h2>Engeneer</h2>
      <a href="#">contact us</a>
    </div>
    <div class="second">
      <p>Section Second Top Line</p>
    </div>
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </section>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  //   name: "Home",
  //   components: {
  //     HelloWorld
  //   }
};
</script>

<style>
* {
  text-decoration: none;
  margin: 0;
}

.home {
  text-align: center;
  letter-spacing: 1px;
}

.first {
  background-image: url(../assets/homeshot.jpg);
  background-size: cover;
  height: 100vh;
  width: 100vw;
}

.first h1 {
  display: block;
  color: #fff;
  font-size: 300%;
  padding: 40vh 0 0 0;
}

.first h2 {
  display: block;
  color: #fff;
  font-size: 200%;
  padding: 0 0 100px 0;
}

.first a {
  color: #fff;
  font-size: 16px;
  padding: 20px 40px;
  border: 2px solid #fff;
  border-radius: 3px;
  text-transform: uppercase;
}

.first a:hover {
  border: 2px solid #40e0d0;
  transition: 0.8s;
}

.second {
  height: 100vh;
}
</style>