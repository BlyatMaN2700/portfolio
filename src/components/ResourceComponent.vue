<template>
  <div class="resource">
    <h2>
      <slot name="name"></slot>
    </h2>
    <h3>Descriptif</h3>
    <slot name="descriptif"></slot>
    <h3>Compétences ciblées</h3>
    <slot name="competences"></slot>
    <h3>Projets liés</h3>
    <slot name="projects"></slot>
    <h3>Volume horaire</h3>
    <slot name="hours"></slot>
  </div>
</template>
