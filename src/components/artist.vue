<template>
  <div>
              <img
                :src="profile_picture"
                :alt="name"
                class="aspect-square object-cover"
                width="300"
                height="300"
              />
              <div class="p-2 bg-gray-300 text-black">
                <h3 class="text-lg font-bold">{{ name }}</h3>
                <p class="text-sm text-muted-foreground">{{ description }}</p>
              </div>
  </div>
</template>

<script>
export default {
  name: 'ArtistComp',
  props: {
    name: String,
    description: String,
    profile_picture: String
  }

}
</script>
