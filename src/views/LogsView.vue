<script setup>
import { ArrowLeftIcon } from '@heroicons/vue/solid'
</script>

<template>
  <header>
    <nav class="p-5 flex items-center justify-between bg-slate-600">
      <button class="opacity-50 hover:opacity-100" onclick="window.location.href='/'">
        <ArrowLeftIcon class="h-8 w-8 text-white" />
      </button>
      <RouterLink to="/" class="pl-4">
        <div class="w-10 h-10">
          <img class="rounded-full" src="https://randomuser.me/api/portraits/men/81.jpg" />
        </div>
      </RouterLink>
      <div />
      <div class="flex gap-4 pr-14">
        <RouterLink to="/about" class="text-white text-lg font-semibold">About</RouterLink>
        <RouterLink to="/logs" class="text-white text-lg font-semibold">Logs</RouterLink>
      </div>
      <div />
    </nav>
  </header>
  <div class="absolute w-full h-full bg-slate-800">
    <div class="relative flex flex-col w-full h-full items-center justify-start gap-y-8 my-10 bg-slate-800">
      <div class="flex flex-col justify-start bg-slate-600 rounded-[20px] p-6 gap-8 w-1/2">
        <h1 class="text-white font-bold text-xl">Logs</h1>
        <p class="text-white"></p>
      </div>
      <div class="flex flex-col justify-start bg-slate-600 rounded-[20px] p-6 gap-8 w-1/2">
        <h1 class="text-white font-bold text-xl">Project</h1>
        <div class="grid grid-cols-1 divide-y-2 text-white align-text-bottom">
          <span class="pb-1">Age : 21 years old</span>
          <span class="pt-2 pb-1">Email : zhafranjupleks5758@gmail.com</span>
          <span class="pt-2 pb-1">Role : Backend Engineer</span>
          <hr>
        </div>
      </div>
    </div>
  </div>
</template>