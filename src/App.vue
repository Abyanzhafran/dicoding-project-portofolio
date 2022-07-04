<script setup>
import { RouterView } from 'vue-router'

defineProps({
  navHome: {
    default: false,
    type: Boolean
  }
})

// const currentUrl = () => {
//   window.location.href
// }
// console.log(currentUrl())
</script>

<template>
  <!-- <header>
    <nav class="p-6 flex items-center justify-between bg-slate-800">
      <div />
      <div class="flex items-center justify-between">
        <RouterLink to="/">
          <div class="w-10 h-10">
            <img class="rounded-full" src="https://randomuser.me/api/portraits/men/81.jpg" />
          </div>
        </RouterLink>
        <div class="flex gap-2">
          <RouterLink to="/about" class="text-white text-lg font-semibold">About</RouterLink>
          <RouterLink to="/logs" class="text-white text-lg font-semibold">Logs</RouterLink>
        </div>
      </div>
      <div />
    </nav>
  </header> -->

  <RouterView />
</template>
