<template>
  <h1>{{ msg }}</h1>
  <img
    class="jumbo"
    src="../assets/images/The-Progressive-JavaScript-Framework.png"
    alt="Vue Logo Jumbotron"
  />
</template>

<script>
export default {
  name: "jumbo",
  data() {
    return {
      titoloBottone: "bottone",
      msg: "Hello Vue",
    };
  },
  methods: {
    consoleDebug() {
      console.log("debug");
    },
  },
};
</script>
<style>
.jumbo {
  width: 100%;
  height: 100%;
}
</style>
