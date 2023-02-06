<template>
  <div>
    <div class="grid grid-cols-4 gap-5">
      <div v-for="product in products" :key="product.id">
        <ProductCard :product="product" />
      </div>
    </div>
  </div>
</template>

<script setup>
definePageMeta({
  layout: 'products',
})

// Fetch the products
const { data: products } = await useFetch('https://fakestoreapi.com/products')

// Overwrite default meta
useHead({
  title: 'Owlie Nuxt | Merch',
  meta: [{ name: 'description', content: 'All of Nuxt 3 Merch' }],
})
</script>

<style scoped></style>
