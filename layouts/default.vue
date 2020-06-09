<template>
  <div
    class="resume two-pages margin flex-col md:flex-row md:items-stretch print:flex-row"
  >
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

h3 {
  @apply text-lg;
}

p {
  @apply text-base;
}
</style>

<style>
.resume {
  @apply flex min-h-screen;
}
</style>

<style>
@page {
  size: A4;
  margin: 10mm;
}

@media print {
  .resume {
    height: 297mm;
  }

  .resume.margin {
    height: 277mm;
  }

  .resume.two-pages {
    height: 594mm;
  }

  .resume.two-pages.margin {
    height: 554mm;
  }

  .resume.three-pages {
    height: 891mm;
  }

  .resume.three-pages.margin {
    height: 831mm;
  }

  .print-hidden {
    display: none;
  }
}
</style>
