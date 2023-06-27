<template>
    <div>
      <header class="shadow-sm bg-white">
        <nav class="container flex mx-auto p-4 justify-between">
          <NuxtLink to="/products">Web Products</NuxtLink>
          
        </nav>
      </header>
  
      <!-- it will output the default layout -->
      <div class="container mx-auto p-4">
      <slot/>
      </div>
      <footer class="container flex justify-between p-4 mx-auto border-t-2">
        <ul class="flex gap-4">
            <li><NuxtLink to="/">Home</NuxtLink></li>
            <li><NuxtLink to="/about">About</NuxtLink></li>
            <li><NuxtLink to="/products">Products</NuxtLink></li>
          </ul>
      </footer>
    </div>
  </template>
  
  <style scoped>
    .router-link-exact-active{
      color: #12b488;
    }
  </style>