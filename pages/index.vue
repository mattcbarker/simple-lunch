<template>
  <div class="container">
    <div>
      <h1 class="title">
        Simple-Lunch
      </h1>
      <h2 class="subtitle">
        Coming Soon
      </h2>

    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-image: radial-gradient(#efebeb, #aab5aa);
}

.title {
  font-family: 'Saira Extra Condensed', sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #5cB8B2;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
