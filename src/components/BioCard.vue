<template>
  <section class="mx-auto w-64 m-4 flex-shrink-0 md:m-4">
    <div class="bg-gray-300 border rounded-full h-64">
    </div>
    <div class="h-16 pt-4">
      <div class="font-display font-bold">{{ name }}</div>
      <p class="font-body font-light">{{ title }}</p>
    </div>
  </section>
</template>

<style scoped>
</style>

<script>
export default {
  name: 'BioCard',
  props: [
    'name',
    'title'
  ]
}
</script>
