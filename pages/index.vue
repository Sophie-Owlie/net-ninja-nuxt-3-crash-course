<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Owlie Nuxt Boutique</NuxtLink>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
        <a href="/about">normal link -- about page</a>
      </nav>
    </header>

    <h2>Home</h2>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente saepe
      blanditiis dolore reiciendis, aliquam officiis ad totam neque recusandae
      aspernatur voluptates ex dignissimos pariatur cum, omnis praesentium velit
      ullam possimus.
    </p>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti,
      dignissimos! Vero voluptas nostrum corrupti, assumenda culpa quidem
      voluptatibus dolorum, possimus cum doloribus nisi ad accusamus blanditiis
      animi molestias at aliquid!
    </p>
  </div>
</template>

<script setup></script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
