<script setup>
import { RouterLink, RouterView } from 'vue-router'
// this imports the route of the pages used in the navbar
</script>

<template>
  <div>
  <!-- this is the container for the banner -->
    <header class="flex items-center justify-between bg-gradient-to-l from-teal-700 via-neutral-400 to-stone-600">
    <!-- This contains the logo and the nav links -->
    <img alt="Vue logo" class="p-2 pl-7" src="@/assets/images/logo.svg" width="125" height="125" />

    <div class="pr-7">
    <!-- this is the container for nav bar -->
      <nav class="flex items-center justify-end">
        <ul class="flex gap-4">
        <li>
          <RouterLink to="/" class="text-xl font-semibold text-slate-900">Home</RouterLink>
        </li>
        <li>
          <RouterLink to="/about" class="text-xl font-semibold text-slate-900">About</RouterLink>
        </li>
      </ul>
      </nav>
    </div>
    </header>
  </div>

  <RouterView />
  <!-- this links the nav to it's designated pages -->
</template>

