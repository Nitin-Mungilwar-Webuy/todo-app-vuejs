<script setup>
// import HelloWorld from "./components/HelloWorld.vue";
// import TheWelcome from "./components/TheWelcome.vue";
import Home from "./components/Home.vue";
import AboutUs from "./components/AboutUs.vue";
</script>

<template>
  <header>
    <img
      alt="Vue logo"
      class="logo"
      src="./assets/logo.svg"
      width="50"
      height="50"
    />

    <div class="wrapper">
      <!-- <HelloWorld msg="You did it!" /> -->
      <Home />
      <AboutUs />
    </div>
  </header>

  <main>
    <!-- <TheWelcome /> -->
  </main>
</template>
