<script setup>
// import TheWelcome from '../components/TheWelcome.vue';
import Header from '../components/Header.vue';
import List from '../components/List.vue';
import Footer from '../components/Footer.vue';

const name = {
  label: "Andromeda",
  description: "Beddazled like the sky."
}
</script>

<template>
  <div class="flex flex-col h-screen justify-between">
  <Header :title="name.label" class="bg-gradient-to-br from-slate-900 to-emerald-500 bg-clip-text py-4 pl-7 text-3xl font-extrabold text-transparent lg:text-5xl"> 
  </Header>

  <main class="flex flex-col items-center">
    <h1 class="pb-10 text-4xl">Beddazled like the sky.</h1>

    <img alt="three gold rings"  class="h-80" src="@/assets/images/jewelry.jpg" />
    
    <List />
  </main>

  <Footer class="grid h-20 place-items-center bg-gradient-to-l from-teal-700 via-neutral-400 to-stone-600 text-white text-2xl">&copy; 2022 Myka Peligrino</Footer>
  </div>
  

  

  
</template>
