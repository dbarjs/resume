<template>
  <section>
    <h2>Formação Acadêmica</h2>
    <article class="education">
      <h3 class="education-school">FGV</h3>
      <p class="education-degree">MBA em Gestão Empresarial</p>
      <p class="education-time">2018 - 2020</p>
      <p class="education-city">Londrina, Paraná</p>
      <p class="education-description"></p>
    </article>
    <article class="education">
      <h3 class="education-school">Universidade Paulista</h3>
      <p class="education-degree">Ciência da Computação</p>
      <p class="education-time">2010 - 2014</p>
      <p class="education-city">Assis, São Paulo</p>
      <p class="education-description"></p>
    </article>
  </section>
</template>

<script>
export default {}
</script>

<style>
.education {
  @apply mb-8;
}

.education-school,
.education-degree,
.education-description {
  @apply text-black;
}

.education-city,
.education-time,
.education-description {
  @apply text-sm;
}

.education-city {
  @apply text-gray-500;
}

.education-description {
  @apply mt-3;
}
</style>
