<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container flex mx-auto justify-between p-4">
        <NuxtLink class="font-bold" to="/">Web</NuxtLink>
        <ul class="flex gap-4">
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink class="btn" to="/products">Products</NuxtLink></li>
        </ul>
      </nav>
    </header>

    <!-- it will output the default layout -->
    <div class="container mx-auto">
      <slot />
    </div>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
