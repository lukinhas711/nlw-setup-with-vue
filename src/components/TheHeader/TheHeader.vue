<script setup lang="ts">
import { TheContainer } from '../TheContainer'
import HeaderColors from './HeaderColors.vue'
const add = () => {
  alert('adicionar um hábito')
}
</script>

<template>
  <section class="flex justify-between items-center gap-4 min-w-[350px] mt-32 lg:min-w-[1024px]">
    <section class="flex flex-col gap-1">
      <HeaderColors />
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