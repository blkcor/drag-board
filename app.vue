<script setup lang="ts">
useServerSeoMeta({
  title: 'My Amazing Site',
  ogTitle: 'My Amazing Site',
  description: 'This is my amazing site, let me tell you all about it.',
  ogDescription: 'This is my amazing site, let me tell you all about it.',
  ogImage: 'https://vueschool.io/img/logo/vueschool_logo_multicolor_negative.svg',
  twitterCard: 'summary_large_image',
})
</script>
<template>
  <div class="p-10 h-[100vh] bg-teal-600 overflow-auto">
    <h1 class="text-4xl text-white flex items-center mb-10">
      <img width="200" class="mr-3" src="https://vueschool.io/img/logo/vueschool_logo_multicolor_negative.svg"
        alt="Vue School" />
    </h1>
    <TrelloBoard />
  </div>
</template>
