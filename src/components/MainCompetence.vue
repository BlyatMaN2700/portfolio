<script setup>
import { ref } from 'vue'
import '@material/web/all'

import { styles as typescaleStyles } from '@material/web/typography/md-typescale-styles.js'

document.adoptedStyleSheets.push(typescaleStyles.styleSheet)

const show = ref(true)

function toggle() {
  show.value = !show.value
}
</script>

<template>
  <div class="MainComp">
    <div class="comp">
      <div class="title">
        <MdFilledIconButton toggle @click="toggle">
          <md-icon :class="{ tourne: show }"> Arrow_Forward_iOS </md-icon>
        </MdFilledIconButton>
        <h2>
          <slot name="name"></slot>
        </h2>
      </div>
      <div class="list" :class="{ hidden: !show }">
        <slot name="subComp"> </slot>
      </div>
    </div>
    <h2 class="lvl">
      <div class="level"><slot name="level"></slot></div>
    </h2>
  </div>
</template>

<style>
h2 {
  color: pink;
}

MdFilledIconButton {
  background-color: var(--vt-c-button);
  color: var(--vt-c-text-dark-2);
  border-radius: 50px;
  height: 30px;
  width: 30px;
  text-decoration: none;
  font-weight: bolder;
  text-align: center;
  margin: auto;
  display: grid;
}

MdFilledIconButton md-icon {
  transition: all 0.23s ease-in-out;
}

MdFilledIconButton md-icon.tourne {
  transform: rotate(90deg);
}

md-icon {
  margin: auto;
}

.title {
  display: grid;
  grid-template-columns: 40px auto;
}

ul {
  list-style-type: none;
}

.MainComp {
  margin: 20px;
  border-left: 5px solid var(--color-text);
  padding-left: 15px;
  border-radius: 3px;
  display: grid;
  grid-template-columns: 90% 10%;
}

.lvl {
  display: flex;
  align-items: center;
}

.list {
  transition: all 0.25s ease-in-out;
  transform: scaleY(1);
  transform-origin: top;
  max-height: 1200px;
}

.list.hidden {
  transform: scaleY(0);
  overflow: hidden;
  max-height: 0;
}
</style>
