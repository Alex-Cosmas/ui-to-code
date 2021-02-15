<template>
  <!-- <div class="bg-black text-white py-10">
    <div>
      <nuxt-link to="/">Designs</nuxt-link>
      <nuxt-link to="/tech">Tech</nuxt-link>
      <nuxt-link to="/glossary">Glossary</nuxt-link>
    </div>
  </div> -->
  <div>
    <div class="bg-gray-100 text-gray-800 text-xl">
      <nav class="container mx-auto flex items-center py-5 justify-between">
        <a href="" class="text-3xl">ui-to-code</a>
        <div class="flex">
          <ul class="flex">
            <nuxt-link to="/" class="mx-2 px-3">Design</nuxt-link>
            <nuxt-link to="/dev" class="mx-2 px-3">Dev</nuxt-link>
            <nuxt-link to="/glossary" class="mx-2 px-3">Glossary</nuxt-link>
          </ul>
        </div>
        <button
          class="px-8 py-2 bg-gray-900 rounded-md text-white font-semibold"
        >
          Get in touch
        </button>
      </nav>
    </div>
  </div>
</template>
