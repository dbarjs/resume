<template>
  <div class="flex flex-col md:flex-row md:items-stretch min-h-screen">
    <Header></Header>
    <nuxt />
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
export default {
  components: {
    Header
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

h1 {
  @apply text-4xl;
}

h1 > span {
  @apply block text-lg;
}

h2 {
  @apply text-xl mb-3;
}

p {
  @apply text-base text-gray-700;
}
</style>
