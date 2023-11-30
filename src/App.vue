<script>
import Emit from "./Component/Emit/Parent.vue";
import VueDirective from "./Component/vueDirectives.vue";
export default {
  component: {
    Emit,
    VueDirective,
  },
  name: "App",
  data() {
    return {
      name: "odetayo",
    };
  },
};
</script>

<template>
  <div>
    <Emit />
    <VueDirective />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
