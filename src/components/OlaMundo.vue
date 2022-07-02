<template>
  <h1>Olá mundo!</h1>
  <h2>Meu primeiro projeto em VUE 3</h2>
</template>

<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "OlaMundo"
  });
</script>

<style>
  body {
    padding: 2rem;
    text-align: center;
    font-family: sans-serif;
    background: #222;
  }

  h1 {
    color: cadetblue;
    font-size: 3em;
  }

  h2 {
    color: #41b883;
  }
</style>