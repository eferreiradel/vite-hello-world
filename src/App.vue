<template>
  <div class="row">
    <jumbotron></jumbotron>
  </div>
</template>

<script>
import jumbotron from "./components/jumbotron.vue";
export default {
  name: "hello",
  data() {
    return {
      msg: "Hello Vite",
    };
  },
  components: {
    jumbotron: jumbotron,
  },
};
</script>
<style>
.row {
  justify-content: center;
  justify-content: center;
  width: 100%;
}
</style>
