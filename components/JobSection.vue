<template>
  <article>
    <h2>Experiência</h2>
    <section class="job">
      <h3 class="job-employer">JSBX Consulting</h3>
      <p class="job-title">Consultor</p>
      <p class="job-time">Fevereiro de 2020 - o momento</p>
      <p class="job-city">Paraná</p>
      <p class="job-description">
        A Elbit Digital é uma agência criada por uma equipe apaixonada por Web.
        Nela é feito o desenvolvimento de Websites e Web Apps utilizando
        HTML/CSS, JS, Node.JS, Gulp.JS e Google Firebase. Foram desenvolvidos
        vários projetos Open Source de Frameworks Front End e Back End para
        auxiliar no desenvolvimento de Websites.
      </p>
    </section>
    <section class="job">
      <h3 class="job-employer">Elbit Digital</h3>
      <p class="job-title">Co-Fundador</p>
      <p class="job-time">Fevereiro de 2020 - o momento</p>
      <p class="job-city">Palimtal, SP</p>
      <p class="job-description">
        A Elbit Digital é uma agência criada por uma equipe apaixonada por Web.
        Nela é feito o desenvolvimento de Websites e Web Apps utilizando
        HTML/CSS, JS, Node.JS, Gulp.JS e Google Firebase. Foram desenvolvidos
        vários projetos Open Source de Frameworks Front End e Back End para
        auxiliar no desenvolvimento de Websites.
      </p>
    </section>
  </article>
</template>

<script>
export default {}
</script>

<style>
.job {
  @apply mb-8;
}

.job-employer,
.job-title,
.job-description {
  @apply text-black;
}

.job-city,
.job-time,
.job-description {
  @apply text-sm;
}

.job-city {
  @apply text-gray-500;
}

.job-description {
  @apply mt-3;
}
</style>
