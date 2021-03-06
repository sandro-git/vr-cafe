<template>
  <div class="w-full">
    <h1 class="title text-5xl">{{ jeu.titre }}</h1>
    <div class="flex justify-center w-full">
      <p class="w-1/2 p-8 text-xl">{{ jeu.description }}</p>
      <div class="w-1/2 flex items-center">
        <img
          class="p-4 align-center"
          :src="require(`~/assets/img/${jeu.image}`)"
          alt="alt text"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    order: { type: Number, default: 0 },
  },
  data() {
    return {
      jeu: {
        titre: 'pangman',
        image: 'pangman.jpg',
        description:
          " Lorsque des sphères extraterrestres de l'espace envahissent notre planète bien-aimée, seuls les frères et sœurs Buster tiennent bon ... Pangman vous emmène dans une expérience de jeu d'arcade classique en VR, où votre objectif est de faire éclater autant de sphères que possible en utilisant une paire de pistolets qui transforment  dans les crochets lorsque vous les lancez.Terminez 140 niveaux du mode histoire dans une campagne individuelle ou coopérative et profitez de jeux multijoueurs effrénés avec 'à 8 joueurs.Pangman en 12 mots AMUSEMENT Exploser des sphères tirant sur votre arme et votre crochet tout en modifiant les lois du temps et de la physique est totalement gratifiant NOSTALGIE Revivez 'essence des jeux vidéo classiques en VR. ",
      },
    }
  },
}
</script>
