<template>
  <div>
    <h1>
      Hello {{ baseURL }}
    </h1>
    <a href="/test/">Go to /test/</a>
  </div>
</template>

<script setup>
const baseURL = process.env.NUXT_APP_BASE_URL;
</script>

<style>
html, body {
  height: 100%;
  margin: 0;
}

div {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>