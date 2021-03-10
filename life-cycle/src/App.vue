<template>
  <h1>LifeCycle Hooks</h1>
</template>

<script>
import { onMounted } from "vue";

export default {
  setup() {
    onMounted(() => {
      console.log("Foi montado - composition API");
    });
  },
};

/* export default {
  mounted() {
    console.log("Foi montado - options API sintax");
  },
}; */
</script>

<style></style>
