<template>
  <div class="monk">
    <h1>How to eat ass.</h1>
    <ul>
      <li>Step 1: Remove dem clothes</li>
      <li>Step 2: Open dat mouth</li>
      <li>Step 3: Go for it tiger</li>
      <li class="hobo" > i eat ass</li>
      <!-- that was pissing me off -->
    </ul>

    <AssEater />
    <p class="text"> I would like to thank Jingle Bells for coding 95% of this website , this was a team effort </p>
  </div>
</template>

<style>
.text {
  color: white;
}
  .monk {
    background-image: url("./assets/download.jpg");
    height: 100vh;
    width: 100vw;
    margin: 0;
    padding: 0;
  }
  .hobo {
    background-color: yellow;
  }
</style>

<script>
import AssEater from './components/AssEater.vue'

export default {
  name: 'App',
  components: {
    AssEater
  }
}
</script>
