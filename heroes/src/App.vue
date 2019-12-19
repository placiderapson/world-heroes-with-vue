<template>
  <div id="app">
    <h1 id="app__title">World's Well-Known Heroes</h1>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;

  &__title {
    text-transform: uppercase;
  }
}
</style>
