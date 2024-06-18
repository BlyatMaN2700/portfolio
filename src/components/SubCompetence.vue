<script setup>
import { ref } from 'vue'

const show = ref(false)

function toggle() {
  show.value = !show.value
}
</script>

<template>
  <div class="subComp">
    <div class="title">
      <MdFilledIconButton @click="toggle">
        <md-icon :class="{ tourne: show }"> Arrow_Forward_iOS </md-icon>
      </MdFilledIconButton>
      <h3>
        <slot name="name"></slot>
      </h3>
    </div>
    <div class="list2" :class="{ hidden: !show }">
      <h4>Ressources liées</h4>
      <slot name="resources"></slot>
      <h4>Projets liés</h4>
      <slot name="projects"></slot>
      <h4>Auto-évaluation</h4>
      <slot name="feeling"></slot>
    </div>
    <div class="level">
      Niveau d'acquisition :
      <slot name="level"></slot>
    </div>
  </div>
</template>

<style>
h3 {
  color: white;
}

h4 {
  color: whitesmoke;
}

.list2 {
  transition: all 0.23s ease-in-out;
  transform: scaleY(1);
  transform-origin: top;
  max-height: 500px;
}

.list2.hidden {
  transform: scaleY(0);
  overflow: hidden;
  max-height: 0;
}
</style>
