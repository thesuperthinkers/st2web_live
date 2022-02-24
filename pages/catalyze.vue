<template>
  <section class="text-gray-600 body-font overflow-hidden">
    <div class="container px-5 py-24 mx-auto">
      <!-- hero image -->
      <div class="bg-gray-200 h-64 w-full rounded"></div>

      <!-- blog section -->
      <div class="p-12 md:w-3/4 mx-auto flex-col items-start">
        <span
          class="inline-block py-1 px-2 rounded bg-green-50 text-green-500 text-xs font-medium tracking-widest"
          >CATALYZE</span
        >
        <h2 class="sm:text-3xl text-2xl title-font font-medium text-gray-900 mt-4 mb-4">
          Learning about technology is preparing for future success
        </h2>
        <p class="leading-relaxed mb-8">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt, quos officiis
          fugiat eum minus quia exercitationem ut, quibusdam quaerat ducimus eos debitis!
          Maiores modi facilis recusandae consequuntur assumenda corporis nulla aliquid
          natus corrupti eius deserunt, consectetur inventore mollitia ab blanditiis ad
          hic, fuga, qui error eveniet adipisci praesentium quidem. Ducimus asperiores
          cumque eveniet numquam quod eos fuga est cupiditate earum qui incidunt, debitis
          labore illum. Aspernatur quia itaque nesciunt voluptatibus voluptates animi
          ducimus consectetur! Obcaecati quia reiciendis praesentium similique commodi
          nulla iure quae mollitia aut laboriosam quod optio ipsa at odio, laudantium sed
          quis incidunt quidem magnam unde? Rerum, sint!
        </p>
        <div
          class="flex items-center flex-wrap pb-4 mb-4 border-b-2 border-gray-100 mt-auto w-full"
        >
          <nuxt-link to="/innovation">
            <button
              class="flex mx-auto text-white bg-green-500 border-0 py-2 px-8 focus:outline-none hover:bg-green-600 rounded text-lg"
            >
              Register Now
            </button>
          </nuxt-link>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  layout: "default",
};
</script>

<style></style>
