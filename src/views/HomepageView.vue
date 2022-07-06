<script setup>

</script>

<template>
  <main>
    <div class="absolute w-full h-screen bg-slate-800"></div>
    <div class="relative flex flex-col w-full h-screen items-center justify-center gap-y-4">
      <div class="w-32 h-32">
        <img class="rounded-full" src="https://randomuser.me/api/portraits/men/81.jpg" />
      </div>
      <div class="flex flex-col items-center gap-2">
        <span class="text-white font-bold text-2xl">Hello, I'm Zhafran</span>
        <span class="text-white font-base text-lg">Software Engineer</span>
      </div>
      <RouterLink to="/about" class="bg-transparent rounded-full">
        <div class="px-4">
          <span class="text-gray-500 hover:text-gray-400 text-xl font-semibold opacity-100">/about me</span>
        </div>
      </RouterLink>
      <div class="flex gap-4 mt-6">
        <button onclick="window.open('https://github.com/Abyanzhafran')">
          <img src="github_logo.png" class="w-14 h-14">
        </button>
        <button onclick="window.open('https://www.linkedin.com/in/zhafran-daffa-47b8491a0/')">
          <img src="linkedin_logo.png" class="w-9 h-9">
        </button>
        <button onclick="window.open('https://www.instagram.com/abyanzhafran__/')">
          <img src="instagram_logo.png" class="w-12 h-12">
        </button>
      </div>
    </div>
  </main>
</template>
