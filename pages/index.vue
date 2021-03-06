<template>
  <div class="container flex-col justify-between">
    <TheImage />
    <TheImage />
    <h1 class="title">{{ jeu.titre }}</h1>
    <div class="w-full flex justify-center border border-gray-100">
      <p class="w-1/2 border border-gray-100">{{ jeu.texte }}</p>
      <img
        class="w-1/2 border border-gray-100 order-first"
        :src="require(`~/assets/img/${jeu.image}`)"
        alt="alt text"
      />
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
        texte: 'lorem ipsum',
      },
    }
  },
}
// import axios from 'axios'

// export default {
//   data() {
//     return {
//       restaurants: [],
//       error: null,
//     }
//   },
//   async mounted() {
//     try {
//       const response = await axios.get('http://localhost:1337/restaurants')
//       this.restaurants = response.data
//     } catch (error) {
//       this.error = error
//     }
//   },
// }
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS */

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
