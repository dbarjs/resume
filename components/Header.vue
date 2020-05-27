<template>
  <header class="header p-6 md:pt-12 bg-gray-800 text-white">
    <section>
      <h2>Contato</h2>
      <p>Bandeirantes - PR</p>
      <p>
        <a href="tel:+5543999752470">+5543999752470</a>
        <span class="text-gray-500">(Celular, WhatsApp)</span>
      </p>
      <p>
        <a href="mailto:joseeduardobarros@gmail.com">
          joseeduardobarros@gmail.com
        </a>
      </p>
    </section>
    <section>
      <p>
        <a href="https://www.linkedin.com/in/dbarjs/">
          www.linkedin.com/in/dbarjs
        </a>
        <span class="text-gray-500">(LinkedIn)</span>
      </p>
      <p>
        <a href="https://dbar.js.org/">
          dbar.js.org
        </a>
        <span class="text-gray-500">(Website)</span>
      </p>
      <p>
        <a href="https://t.me/dbarjs">@dbarjs</a>
        <span class="text-gray-500">(Telegram)</span>
      </p>
    </section>
  </header>
</template>

<script>
export default {}
</script>

<style>
.header {
  @apply relative flex flex-col min-h-full;
}

.header p {
  @apply text-white;
}

.header section {
  @apply mb-4;
}
</style>
