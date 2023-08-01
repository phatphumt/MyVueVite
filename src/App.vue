<template>
  <nav class="text-center py-2 text-blue-800">
    <router-link to="/">Home</router-link> <span class="font-bold text-black"> | </span> <router-link
      to="/about">About</router-link>
    <span class="font-bold text-black"> | </span>
    <router-link to="/contact">Contact</router-link>
  </nav>
  <main>
    <router-view />
  </main>
</template>

