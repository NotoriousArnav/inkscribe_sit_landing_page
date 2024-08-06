<template>
  <section>
    <div class="container px-4 md:px-6">
      <div class="flex flex-col items-center justify-center space-y-4 text-center">
          <div class="space-y-2">
            <div class="inline-block rounded-lg bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 px-3 py-1 text-sm text-white">
              Inkscribe Gallery
            </div>
            <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 bg-clip-text text-transparent">
              Explore the Creativity of Our Inkscribe Artists
            </h2>
            <p class="max-w-[900px] text-muted-foreground md:text-xl/relaxed lg:text-base/relaxed xl:text-xl/relaxed">
              Browse through a curated selection of artwork, ranging from poems and portraits to music and mixed
              media.
            </p>
          </div>
        </div>
    </div>
    

<div class="mx-auto grid max-w-5xl items-center gap-6 py-12 lg:grid-cols-3 lg:gap-12">
  <GalleryArtComp 
   title="Artwork 1"
   description="Artwork made by Arnav Ghosh"
   image_link="/placeholder.svg"
   class="rounded-lg overflow-hidden border-2 border-black"
  />

  <GalleryArtComp 
   title="Artwork 2"
   description="Artwork made by Arnav Ghosh"
   image_link="/placeholder.svg"
   class="rounded-lg overflow-hidden border-2 border-black"
  />

  <GalleryArtComp 
   title="Artwork 3"
   description="Artwork made by Arnav Ghosh"
   image_link="/placeholder.svg"
   class="rounded-lg overflow-hidden border-2 border-black"
  />
</div>

  </section>
</template>

<script>
import GalleryArtComp from './gallery_art.vue'
export default {
  name: 'GalleryComp',
  components: {
    GalleryArtComp
  }
}
</script>
