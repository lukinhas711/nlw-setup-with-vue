<script setup lang="ts">
import { TheContainer } from '../TheContainer'
const add = () => {
  alert('adicionar um hábito')
}
</script>

<template>
  <section class="flex justify-between items-center gap-4 min-w-[350px] mt-32 lg:min-w-[1024px]">
    <section class="flex flex-col gap-1">
      <div class="flex items-center gap-1">
        <span class="w-3 h-3 rounded-sm border border-zinc-500 bg-zinc-800"></span>
        <span class="w-3 h-3 rounded-sm border border-violet-700 bg-violet-700"></span>
        <span class="w-3 h-3 rounded-sm border border-violet-600 bg-violet-600"></span>
        <span class="w-3 h-3 rounded-sm border border-violet-500 bg-violet-500"></span>
        <span class="w-3 h-3 rounded-sm border border-violet-400 bg-violet-400"></span>
        <span class="w-3 h-3 rounded-sm border border-violet-300 bg-violet-300"></span>
      </div>
      <h1 class="text-3xl font-black lg:text-4xl">
        habits
      </h1>
    </section>
    <section>
      <button class="flex items-center justify-center gap-1 border border-violet-500 p-2 rounded-md" @click="add()">
        <span class="text-2xl text-violet-500">+</span>Novo<span class="hidden lg:inline">hábito</span>
      </button>
    </section>
  </section>
</template>