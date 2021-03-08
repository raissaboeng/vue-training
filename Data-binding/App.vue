<template>
  <div>
    <h1 :style="{ textDecoration }">Hello {{ name }}!</h1>
    <input type="text" v-model="name" />
    <br />
    <a :href="link">Link para o curso!</a>
  </div>
</template>

<script>
export default {
  data: () => ({
    name: "Raissa",
    link: "http://treinamento.vuejsbrasil.org",
    textDecoration: "underline",
  }),
};
</script>

<style>
</style>