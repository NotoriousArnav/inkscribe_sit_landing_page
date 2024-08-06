<template>
  <div class="flex flex-col min-h-[100dvh]">
    <HeaderComp />
    <main class="flex-1">
      <HeroComp />
      <FeaturedComp class="w-full py-12 md:py-24 lg:py-32 bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 text-white" />
      <GalleryComp class="w-full py-12 md:py-24 lg:py-32" />
    </main>
  </div>
</template>

<script>
import HeaderComp from './components/header.vue'
import HeroComp from './components/hero.vue'
import FeaturedComp from './components/featured.vue'
import GalleryComp from './components/gallery.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    HeroComp,
    FeaturedComp,
    GalleryComp
  }
}
</script>


