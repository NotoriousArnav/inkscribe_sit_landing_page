<template>
<header class="px-4 lg:px-6 h-14 flex items-center bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 text-white">
    <a class="flex items-center justify-center gap-2" href="#" rel="ugc">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        stroke-linecap="round"
        stroke-linejoin="round"
        class="h-6 w-6"
      >
        <circle cx="13.5" cy="6.5" r=".5" fill="currentColor"></circle>
        <circle cx="17.5" cy="10.5" r=".5" fill="currentColor"></circle>
        <circle cx="8.5" cy="7.5" r=".5" fill="currentColor"></circle>
        <circle cx="6.5" cy="12.5" r=".5" fill="currentColor"></circle>
        <path d="M12 2C6.5 2 2 6.5 2 12s4.5 10 10 10c.926 0 1.648-.746 1.648-1.688 0-.437-.18-.835-.437-1.125-.29-.289-.438-.652-.438-1.125a1.64 1.64 0 0 1 1.668-1.668h1.996c3.051 0 5.555-2.503 5.555-5.554C21.965 6.012 17.461 2 12 2z"></path>
      </svg>
      <span class="">Inkscribe (Under Construction)</span>
    </a>
    <nav class="ml-auto flex gap-4 sm:gap-6">
      <a class="text-sm font-medium hover:underline underline-offset-4" href="#" rel="ugc">
        Featured Artists
      </a>
      <a class="text-sm font-medium hover:underline underline-offset-4" href="#" rel="ugc">
        Events
      </a>
      <a class="text-sm font-medium hover:underline underline-offset-4" href="#" rel="ugc">
        Gallery
      </a>
      <a class="text-sm font-medium hover:underline underline-offset-4" href="#" rel="ugc">
        About
      </a>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComp'
}
</script>
