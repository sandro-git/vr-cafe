<template>
  <div
    class="flex justify-between bg-gray-800 w-screen h-20 border border-gray-100"
  >
    <h1 class="text-4xl flex items-center border border-gray-100">
      <nuxt-link class="text-2xl font-light m-6" to="/">Logo</nuxt-link>
    </h1>
    <div class="flex items-center border border-gray-100">
      <nuxt-link class="text-2xl font-light m-6" to="/jeux">Nos jeux</nuxt-link>
      <nuxt-link class="text-2xl font-light m-6" to="/tarifs"
        >Nos tarifs</nuxt-link
      >
      <nuxt-link class="text-2xl font-light m-6" to="/cafe">Cafe</nuxt-link>
      <nuxt-link class="text-2xl font-light m-6" to="/contact"
        >Contact</nuxt-link
      >
    </div>
  </div>
</template>

<script>
export default {}
</script>
