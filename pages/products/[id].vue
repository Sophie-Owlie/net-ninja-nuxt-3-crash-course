<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti fuga
      assumenda nam consequatur reiciendis officia tempora nemo voluptatem
      praesentium ipsa, sit reprehenderit libero deserunt! Minus odio non
      voluptatibus quia consectetur.
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params
</script>

<style scoped></style>
