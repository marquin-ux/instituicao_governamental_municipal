<script setup>

import { ref } from 'vue'

const menuOpen = ref(false)

</script>

<template>
  <header
    class="w-full bg-azul-claro text-white px-6 py-2 flex flex-col md:flex-row md:justify-between md:items-center gap-4">

    <!-- Top bar -->
    <div class="flex justify-between items-center">
      <div class="text-lg font-bold md:text-2xl">Arquitetura de Redes de Computadores</div>

      <!-- Botão Hamburguer -->
      <button class="md:hidden" @click="menuOpen = !menuOpen">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </div>

    <!-- Navbar Links -->
    <nav :class="[
      'flex flex-col md:flex-row gap-4 md:gap-6',
      menuOpen ? 'block' : 'hidden md:flex'
    ]">
      <a href="#oque" class="hover:text-gray-400">O que é</a>
      <a href="#dominioendereco" class="hover:text-gray-400">Domínio/Endereço</a>
      <a href="#dns" class="hover:text-gray-400">DNS na Internet</a>
      <a href="#problemas" class="hover:text-gray-400">Problemas Comuns</a>
      <a href="#contexto" class="hover:text-gray-400">Contexto</a>
      <a href="#contexto" class="hover:text-gray-400">Fontes</a>
    </nav>

  </header>
</template>

<style scoped>
a {
  transition: color 0.2s;
  cursor: pointer;
}
</style>
