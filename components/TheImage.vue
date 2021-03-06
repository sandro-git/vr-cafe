<template>
  <div class="w-full">
    <h1 class="title">{{ jeu.titre }}</h1>
    <div class="flex justify-center w-full">
      <p class="w-1/2">{{ jeu.description }}</p>
      <div class="w-1/2">
        <img :src="require(`~/assets/img/${jeu.image}`)" alt="alt text" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      jeu: {
        titre: 'pangman',
        image: 'pangman.jpg',
        description:
          " Lorsque des sphères extraterrestres de l'espace envahissent notre planète bien-aimée, seuls les frères et sœurs Buster tiennent bon ... Pangman vous emmène dans une expérience de jeu d'arcade classique en VR, où votre objectif est de faire éclater autant de sphères que possible en utilisant une paire de pistolets qui transforment  dans les crochets lorsque vous les lancez.Terminez 140 niveaux du mode histoire dans une campagne individuelle ou coopérative et profitez de jeux multijoueurs effrénés avec 'à 8 joueurs.Pangman en 12 mots AMUSEMENT Exploser des sphères tirant sur votre arme et votre crochet tout en modifiant les lois du temps et de la physique est totalement gratifiant NOSTALGIE Revivez 'essence des jeux vidéo classiques en VR. FACILE Commandes simplifiées, adaptées aux débutants en VR.  Cependant, maîtriser le gameplay nécessite beaucoup de pratique. DIRECT Pas de temps de chargement ni de tutoriels complexes.  Mécanique et gameplay intuitifs. MALADIE l'action se déroule dans une simulation d'arcade et il n'y a pas besoin de bouger, donc il n'y a pas de possibilité de mal des transports HUMOUR Script bourré d'humour, de jeux de mots idiots et de nombreuses références à la culture générale, aux jeux vidéo classiques et à la saga Matrix. SOCIAL Le mode histoire peut être joué en mode coopératif et il existe également un mode arène pour des jeux sans fin avec jusqu'à 8 joueurs. ÉCHELLE DE LA CHAMBRE Pangman peut être joué même assis.  Mais si vous disposez d'un espace de 2x2 mètres, vous passerez un bon moment à esquiver les sphères. MATRICE L'histoire et les personnages sont vaguement inspirés de la saga The Matrix, ainsi que du 'Dynamic Timer', un power-up au ralenti qui nous emmène dans l'univers de The Matrix.REJOUABILITÉ Le mode histoire comprend 140 niveaux qui peuvent être joués seul ou en mode coopératif.  Il est également inclus un mode en ligne infini. MAGNIFIQUE Graphiques de dessin animé simples mais attrayants, lumineux et colorés. DES SONS Effets sonores 3D de Spatializer.  Bande sonore originale comprenant 30 thèmes différents.",
      },
    }
  },
}
</script>
