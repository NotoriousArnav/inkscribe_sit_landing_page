<template>
<div >
                <div class="rounded-full bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 px-3 py-1 text-white">
                  {{ datetime }}
                </div>
                <div>
                  <h4 class="text-lg font-medium">
                    {{ title }}
                  </h4>
                  <p class="text-sm text-muted-foreground">
                    {{ description }}
                  </p>
                </div>
                <a
                  class="inline-flex items-center justify-center rounded-md bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 px-4 py-2 text-sm font-medium text-white shadow transition-colors hover:opacity-80 focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50"
                  href="#"
                  rel="ugc"
                >
                  Register
                </a>
              </div> 
</template>

<script>
export default {
  name: 'EventComp',
  props: {
    datetime: String,
    title: String,
    description: String
  }
}
</script>
