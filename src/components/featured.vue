<template >
  <section >
    <div class="container px-4 md:px-6">
      <div class="flex flex-col items-center justify-center space-y-4 text-center">
          <div class="space-y-2">
            <div class="inline-block rounded-lg bg-muted px-3 py-1 text-sm">Featured Artists</div>
            <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl">
              Discover the Talent of Our Inkscribe Artists
            </h2>
            <p class="max-w-[900px] text-muted-foreground md:text-xl/relaxed lg:text-base/relaxed xl:text-xl/relaxed">
              Explore the diverse range of artistic styles and mediums showcased by our talented artists. Each piece
              tells a unique story.
            </p>
          </div>
        </div>
    </div>



    <div class="mx-auto grid max-w-5xl items-center gap-6 py-12 lg:grid-cols-2 lg:gap-12">
          <div class="grid grid-cols-2 gap-4">

            <ArtistComp
              name="John Doe"
              description="Artist, Illustrator, and Graphic Designer"
              profile_picture="/placeholder.svg"
              class="rounded-lg overflow-hidden border-2 border-primary"
            />

            <ArtistComp
              name="Jane Doe"
              description="Artist, Illustrator, and Graphic Designer"
              profile_picture="/placeholder.svg"
              class="rounded-lg overflow-hidden border-2 border-primary"
            />

            <ArtistComp
                name="Arnav Ghosh"
                description="Musician and Engineer"
                profile_picture="/placeholder.svg"
                class="rounded-lg overflow-hidden border-2 border-primary"
              />
          </div>
          <div class="space-y-4">

            <div class="grid gap-1">
              <h3 class="text-xl font-bold">Upcoming Art Events</h3>
              <p class="text-muted-foreground">
                Don't miss our upcoming art exhibitions, workshops, and student showcases.
              </p>
            </div>

             <EventComp
              datetime="Aug 11"
              title="Event 1"
              description="Lorem ipsum dolor sit auctor."
              class="grid grid-cols-[auto_1fr_auto] items-center gap-2"
              />

             <EventComp
              datetime="Aug 28"
              title="Event 2"
              description="Lorem ipsum dolor sit auctor."
              class="grid grid-cols-[auto_1fr_auto] items-center gap-2"
              />


          </div>
    </div>
  </section>
</template>

<script>
import ArtistComp from './artist.vue'
import EventComp from './event.vue'

export default {
  name: 'FeaturedComp',
  components: {
    ArtistComp,
    EventComp
  }
}
</script>
