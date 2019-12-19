<template>
  <div id="app">
    <h1 id="app__title">World's Well-Known Heroes</h1>
    <Heroes />
  </div>
</template>

<script>
import Heroes from './components/Heroes';

export default {
  name: 'app',
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
  margin-top: 30px;

  &__title {
    text-transform: uppercase;
  }
}
</style>
