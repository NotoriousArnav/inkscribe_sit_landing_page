<template>
        <section class="w-full py-12 md:py-24 lg:py-32">
      <div class="container px-4 md:px-6">
        <div class="grid gap-6 lg:grid-cols-[1fr_400px] lg:gap-12 xl:grid-cols-[1fr_600px]">
          <img
            src="/placeholder.svg"
            alt="Hero"
            class="mx-auto aspect-video overflow-hidden rounded-xl object-cover sm:w-full lg:order-last lg:aspect-square"
            width="550"
            height="550"
          />
          <div class="flex flex-col justify-center space-y-4">
            <div class="space-y-2">
              <h1 class="text-3xl font-bold tracking-tighter sm:text-5xl xl:text-6xl/none bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 bg-clip-text text-transparent">
                Unleash Your Creativity at Our Inkscribe Gallery
              </h1>
              <p class="max-w-[600px] text-muted-foreground md:text-xl">
                Discover the vibrant and diverse artwork created by talented students, from poems to portraits and
                even music. Explore, appreciate, and support the next generation of artists.
              </p>
            </div>
            <div class="flex flex-col gap-2 min-[400px]:flex-row">
              <a
                class="inline-flex h-10 items-center justify-center rounded-md bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 px-8 text-sm font-medium text-white shadow transition-colors hover:opacity-80 focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50"
                href="#"
                rel="ugc"
              >
                Explore Gallery
              </a>
              <a
                class="inline-flex h-10 items-center justify-center rounded-md border border-input bg-background px-8 text-sm font-medium shadow-sm transition-colors hover:bg-accent hover:text-accent-foreground focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50"
                href="#"
                rel="ugc"
              >
                Upcoming Events
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>  
</template>

<script>
export default {
  name: 'HeroComp'
}
</script>
