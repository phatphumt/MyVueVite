<script lang="ts" setup>
</script>

<template>
  <!-- TODO: Add a icon when on a small screen (640px) -->

  <body class="bg-indigo-50 bg-gradient-to-br from-indigo-50 to-sky-50 h-screen">
    <nav>
      <div class="bg-gradient-to-r from-slate-500 to-slate-800 flex justify-evenly py-3">
        <router-link to="/">
          <h1 class="text-white text-2xl font-bold">Phatphum</h1>
        </router-link>
        <div class="flex justify-evenly items-center gap-5">
          <div class="hidden sm:block">
            <!-- for non-mobile -->
            <router-link to="/about"><span
                class="text-white font-semibold px-3 py-2 rounded-lg hover:bg-slate-800">About</span></router-link>
            <router-link to="/contact"><span class="text-white font-semibold px-3 py-2 rounded-lg hover:bg-slate-800">My
                Work</span></router-link>
          </div>
        </div>
      </div>
    </nav>
    <main class="pt-10">
      <router-view />
    </main>
  </body>
</template>

<style lang="css" scoped></style>
