<script setup></script>

<template>
  <div class="bg-slate-950 text-white h-screen flex flex-col">
    <header class="flex justify-between items-center p-6">
      <div class="text-2xl font-bold">Nolan & Co</div>
      <nav class="flex gap-8 text-sm font-medium">
        <a href="#" class="hover:text-gray-400 hover:underline">Our Work</a>
        <a href="#" class="hover:text-gray-400 hover:underline">Our Services</a>
        <a href="#" class="hover:text-gray-400 hover:underline">Company</a>
        <a href="#" class="hover:text-gray-400 hover:underline">Contact</a>
      </nav>
    </header>

    <div class="flex-grow flex items-center justify-start">
      <h1
        class="ml-7 text-5xl md:text-6xl font-semibold leading-tight text-left px-4"
      >
        Nolan & Co is a digital product<br />
        agency that focuses on strategy<br />
        and design.
      </h1>
    </div>
  </div>
  <div class="bg-white flex justify-center flex-col items-center py-24">
    <p
      class="max-w-lg mx-auto text-5xl md:text-4xl font-medium text-center leading-relaxed"
    >
      Amazing clients have allowed us to produce work we are proud of.
    </p>
    <button
      class="mt-14 px-6 py-3 rounded-3xl text-white bg-black hover:bg-gray-800 transition font-medium scale-100"
    >
      View Our Work
    </button>
  </div>
</template>

<style scoped></style>
