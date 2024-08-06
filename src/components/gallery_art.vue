<template>
  <div class="rounded-lg overflow-hidden">
            <img
              :src="image_link"
              :alt="title"
              class="aspect-square object-cover"
              width="500"
              height="500"
            />
            <div class="p-4 bg-gray-300">
              <h3 class="text-xl font-bold">{{ title }}</h3>
              <p class="text-sm text-muted-foreground">
                {{ description }}
              </p>
            </div>
          </div>
</template>

<script>
export default {
  name: 'GalleryArtComp',
  props: {
    image_link: String,
    title: String,
    description: String
  }
}
</script>
