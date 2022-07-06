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
          <img class="rounded-full"
            src="https://storage.googleapis.com/cogent-tempo-351103.appspot.com/profile-picture.jpg" />
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
  <div class="absolute w-full h-auto bg-slate-800">
    <div class="relative flex flex-col w-full h-auto items-center justify-start gap-y-8 my-12 bg-slate-800">
      <div class="flex flex-col justify-start bg-slate-600 rounded-[20px] p-6 gap-5 w-5/6 md:w-1/2">
        <h1 class="text-white font-bold text-xl">Education</h1>
        <div>
          <span class="text-white text-lg font-semibold">Amikom Yogyakarta University</span>
          <ul class="list-disc list-outside text-white">
            <div class="ml-5 mt-1">
              <li>Computer Science student</li>
            </div>
          </ul>
        </div>
      </div>
      <div class="flex flex-col justify-start bg-slate-600 rounded-[20px] p-6 gap-10 w-5/6 md:w-1/2">
        <h1 class="text-white font-bold text-xl">Organization and Project Experience</h1>
        <div class="flex flex-col gap-5">
          <div>
            <span class="text-white text-lg font-semibold">Amikom Computer Club</span>
            <ul class="list-disc list-outside text-white">
              <div class="ml-5 mt-1">
                <li>Member at Amikom Computer Club</li>
              </div>
            </ul>
          </div>
          <div>
            <span class="text-white text-lg font-semibold">Bersamabisa.id</span>
            <ul class="list-disc list-outside text-white">
              <div class="ml-5 mt-1">
                <li>Frontend Engineer</li>
                <p>Frontend Web developer which build a website from scratch in frontend part. Product application
                  should be responsive on multiple devices such as web, tablet, and mobile.</p>
              </div>
            </ul>
          </div>
          <div>
            <span class="text-white text-lg font-semibold">Bangkit Cloud Computing Engineering Trainee</span>
            <ul class="list-disc list-outside text-white">
              <div class="ml-5 mt-1">
                <li>Cloud Computing</li>
                <p>Google cloud computing trainee. Learning how to use google cloud and its implementation. Working on
                  capstone project with specific details, make backend API using express js and deploy it to google
                  cloud, also work with machine learning path and Android development student for the capstone project.
                </p>
              </div>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>