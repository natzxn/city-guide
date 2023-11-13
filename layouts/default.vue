<script setup>
import Footer from '~/components/global/Footer.vue';
useHead({
  htmlAttrs: {
    lang: 'en',
  },
  meta: [
    { property: 'og:title', content: `a` },
    { name: 'description', content: '' },
    { property: 'og:description', content: '' },
    { property: 'og:url', content: '' },
    { name: 'twitter:title', content: '' },
    { name: 'twitter:description', content: '' },
    { name: 'twitter:site', content: '/' }
  ],
  title: `City guide - Trójmiasto`,
})
</script>

<template>
  <main class="max-w-8xl">
    <slot/>
    <Footer />
  </main>
</template>
