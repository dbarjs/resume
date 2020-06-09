<template>
  <main class="main flex-grow pt-4 pb-6 md:pt-12">
    <div class="container mx-auto px-6 lg:max-w-screen-sm">
      <about-section></about-section>
      <education-section></education-section>
      <experience-section></experience-section>
    </div>
  </main>
</template>

<script>
import AboutSection from '~/components/AboutSection.vue'
import EducationSection from '~/components/EducationSection.vue'
import ExperienceSection from '~/components/ExperienceSection.vue'
export default {
  components: {
    AboutSection,
    EducationSection,
    ExperienceSection
  }
}
</script>

<style>
.main {
  @apply;
}

.main section h2 {
  @apply text-xl pt-3;
  position: relative;
}

.main section h2::before {
  content: '';
  border-bottom: solid 2px #757575;
  width: 2.5rem;
  position: absolute;
  top: 0;
}
</style>

<style>
@media print {
  .main {
    @apply h-full;
    padding-bottom: 0;
    padding-top: 0;
  }
}
</style>
