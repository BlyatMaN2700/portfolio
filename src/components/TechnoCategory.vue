<template>
  <div class="techno">
    <div class="TechTitle">
      <h2 class="TechH2">
        <slot name="name"></slot>
      </h2>
    </div>
    <slot name="techno"></slot>
  </div>
</template>

<style>
.techno {
  background-color: var(--color-background-mute);
  border-radius: 30px;
  padding: 30px;
  padding-top: 10px;
  margin: 20px;
}

.TechTitle {
  width: 100%;
  text-align: center;
}

.TechH2 {
  margin-bottom: 10px;
}
</style>
