<script setup>
import { ref } from 'vue'

const show = ref(true)

function toggle() {
  show.value = !show.value
}
</script>

<template>
  <div class="competence">
    <div class="title">
      <MdFilledIconButton @click="toggle">
        <md-icon :class="{ tourne: show }"> Arrow_Forward_iOS </md-icon>
      </MdFilledIconButton>
      <h2>
        <slot name="name"></slot>
      </h2>
    </div>
    <div class="list3" :class="{ hidden: !show }">
      <h3>Descriptif</h3>
      <slot name="descriptif"></slot>

      <h3>Technologies utilisées</h3>
      <slot name="techno"></slot>

      <h3>Compétences ciblées</h3>
      <slot name="competences"></slot>

      <h3>Ressources liées</h3>
      <slot name="resources"></slot>

      <slot name="link"></slot>
    </div>
  </div>
</template>

<style>
.list3 {
  transition: all 0.23s ease-in-out;
  transform: scaleY(1);
  transform-origin: top;
  max-height: 1300px;
  margin-left: 40px;
}

.list3.hidden {
  transform: scaleY(0);
  display: hidden;
  max-height: 0;
}
</style>
