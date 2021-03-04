<template>
  <div class="w-full">
    <h1 class="title">Accueil</h1>
    <div class="flex justify-center w-full">
      <p class="w-1/2 border border-gray-100">{{ jeu.texte }}</p>
      <img class="w-1/2" :src="jeu.image" alt="alt text" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      jeu: {
        image: 'https://via.placeholder.com/150',
        texte: 'lorem ipsum',
      },
    }
  },
}
</script>
