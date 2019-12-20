<template>
  <div id="app">
    <img src="./assets/superman.svg" alt="Heroes Logo">
    <h1 id="app__title">World's Well-Known Heroes</h1>
    <Heroes />
  </div>
</template>

<script>
import Heroes from './components/Heroes';

export default {
  name: 'App',
  components: {
    Heroes
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #34495E;
  margin: 3rem auto 10rem auto;

  &__title {
    text-transform: uppercase;
  }

  img {
    width: 10rem;
  }
}
</style>
