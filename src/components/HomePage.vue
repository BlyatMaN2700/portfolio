<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <center>
      <img src="..\assets\IMG_20240610_190546.jpg" alt="photo de moi" height="30%" width="40%" />
    </center>
    <h1 class="green" id="name">Noa LIMANDAS</h1>
    <p id="pres">
      Passionné d'informatique et plus précisément de date, je suis actuellement en deuxième année
      de BUT informatique à l'Université Lyon 1. Je suis un parcours Administration, gestion et
      exploitation des données dans le but d'en apprendre le plus possible sur cette facette
      fascinante de l'informatique. Je ne sais pour l'instant pas jusqu'où vont me mener mes études
      mais ce que je sais pour l'instant c'est que je souhaite m'orienter vers les métiers de Data
      Analyst ou de Data Scientist.
    </p>
    <p>
      Bienvenue sur ce site qui a pour but de présenter les compétences que j'ai pu acquérir et les
      projets que j'ai réalisés tout au long de mon parcours scolaire et professionnel.
    </p>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}

.greetings {
  background-color: var(--vt-c-card);
  border-radius: 30px;
  padding: 30px;
  margin: 20px;
  margin-top: 40px;
  display: block;
}

#name {
  text-align: center;
}

p {
  margin: 40px;
}

img {
  border-radius: 100%;
  margin: 40px;
  text-align: center;
}
</style>
