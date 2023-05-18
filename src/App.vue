<template>
  <div class="v-card">
    <subtitle></subtitle>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
import subtitle from "./components/subtitle.vue";
export default {
  name: "hello",
  data() {
    return {
      msg: "Hello Vite",
    };
  },
  components: {
    subtitle: subtitle,
  },
};
</script>
