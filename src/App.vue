<template>
  <div id="app">
    <img alt="Pikachu" src="./assets/pikachu.png" />
    <h1 class="title">Welcome to Pokédex</h1>
    <p>
      The digital encyclopedia created by Professor Oak is an invaluable tool to
      Trainers in the Pokémon world.
    </p>
    <img alt="Get Started" src="./assets/btn-start.png" />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  justify-content: center;
}

.title {
  /*font-family: Lato; esta fuente no la puedo visualizar si no la tengo instalada wn W10*/ 
  font-size: 26px;
  font-style: normal;
  font-weight: 700;
  line-height: 31px;
  letter-spacing: 0em;
  text-align: center;
}
</style>
