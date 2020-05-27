<template>
  <div class="flex-grow">
    <div class="container mx-auto p-6 md:pt-12 lg:max-w-screen-sm">
      <h1 class="mb-6">
        Eduardo Barros
        <span>
          Engenheiro de Software
        </span>
      </h1>
      <h2>Sobre</h2>
      <p>
        Desenvolvedor de Software e estudante de Gestão Empresarial, sou
        completamente apaixonado por Tecnologia, Marketing e Inovação. Atuo como
        desenvolvedor Full Stack em aplicações Web e também como consultor de
        TI.
      </p>
      <job-section></job-section>
    </div>
  </div>
</template>

<script>
import JobSection from '~/components/JobSection.vue'
export default {
  components: {
    JobSection
  }
}
</script>

<style>
article {
  @apply pt-4 pb-6;
}

article h2 {
  @apply text-xl pt-3;
  position: relative;
}

article h2::before {
  content: '';
  border-bottom: solid 1px #9e9e9e;
  width: 2.5rem;
  position: absolute;
  top: 0;
}

article h3 {
  @apply text-lg;
}
</style>
