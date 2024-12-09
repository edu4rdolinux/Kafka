<template>
  <div>
    <pageHeader />
    <Word />
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,opsz,wght@0,6..12,200..1000;1,6..12,200..1000&family=Rubik:ital,wght@0,300..900;1,300..900&display=swap');
@import './styles/variables';

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  color: #f8fefb;
  background-color: $primary-black;
  font-family: "Nunito Sans", serif;
}

.nunito-sans {
  font-family: "Nunito Sans", serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
  font-variation-settings:
    "opsz" 8,
    "wght" 400;
}
</style>

<script setup lang="ts">
useHead({
  title: 'Kafka',
  meta: [
    { name: 'description', content: 'Kafka Music' },
  ],
  link: [
    { rel: 'icon', type: 'image/x-icon', href: '/logo.png' }
  ],
})
</script>