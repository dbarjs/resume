<template>
  <header class="header p-6 min-h-full md:pt-12">
    <section>
      <h2>Contato</h2>
      <p>Bandeirantes - PR</p>
      <p>
        <a href="tel:+5543999752470">+5543999752470</a>
        <span class="observation">(Celular, WhatsApp)</span>
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
        <span class="observation">(LinkedIn)</span>
      </p>
      <p>
        <a href="https://dbar.js.org/">
          dbar.js.org
        </a>
        <span class="observation">(Website)</span>
      </p>
      <p>
        <a href="https://t.me/dbarjs">@dbarjs</a>
        <span class="observation">(Telegram)</span>
      </p>
    </section>
    <section>
      <h2>Top Skills</h2>
      <ul>
        <li>JavaScript</li>
        <li>Vue.js</li>
        <li>PostCSS <span class="divider"></span> Sass</li>
        <li>Firestore <span class="divider"></span> PostgreSQL</li>
        <li>
          GCP <span class="divider"></span> AWS
          <span class="divider"></span> Heroku
        </li>
        <li>Webpack</li>
        <li>Git</li>
      </ul>
    </section>
    <section>
      <h2>Idiomas</h2>
      <ul>
        <li>Português <span class="observation">(Nativo)</span></li>
        <li>Inglês <span class="observation">(Intermediário)</span></li>
      </ul>
    </section>
    <section>
      <h2>Trabalho Voluntário</h2>
      <ul>
        <li>Mozilla Brasil</li>
        <li>Rotaract 4710</li>
        <li>Projeto Empreendendo</li>
      </ul>
    </section>
  </header>
</template>

<script>
export default {}
</script>

<style>
.header {
  @apply relative flex flex-col bg-gray-800 text-white;
}

.header section {
  @apply mb-4;
}

.header h2 {
  @apply mb-2;
}

.header .observation {
  @apply text-gray-500;
}

.header .divider::before {
  @apply text-gray-500;
  content: '/';
  font-size: 0.875rem;
}
</style>

<style>
@media print {
  .header {
    @apply h-full bg-transparent text-gray-900;
    padding: 0;
  }

  .header p,
  .header li {
    @apply text-sm;
  }
}
</style>
