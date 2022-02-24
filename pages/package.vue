<template>
  <section class="text-gray-600 body-font">
    <div class="lg:w-2/3 w-full pb-24 mx-auto overflow-auto">
      <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
          <img
            class="object-cover object-center rounded"
            alt="hero"
            src="https://dummyimage.com/720x600"
          />
        </div>
        <div
          class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center"
        >
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">
            Value Driven <br class="hidden lg:inline-block" />Quality Education
          </h1>
          <p class="mb-8 leading-relaxed">IGCSE</p>
          <div class="flex justify-center">
            <nuxt-link to="contact">
              <button
                class="inline-flex text-white bg-green-500 border-0 py-2 px-6 focus:outline-none hover:bg-green-600 rounded text-lg"
              >
                Inquire
              </button>
            </nuxt-link>
          </div>
        </div>
      </div>
      <table class="table-auto w-full text-left whitespace-no-wrap">
        <thead>
          <tr>
            <th
              class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-100 rounded-tl rounded-bl"
            ></th>
            <th
              class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-100 rounded-tl rounded-bl"
            >
              Play School
            </th>
            <th
              class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-100"
            >
              Head Start
            </th>
            <th
              class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-100"
            >
              Lower Primary
            </th>
            <th
              class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-100"
            >
              Upper Primary
            </th>
            <th
              class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-100"
            >
              Lower Secondary
            </th>
            <th
              class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-100"
            >
              Upper Secondary
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="px-4 py-3">item1</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>
</template>

<script>
export default {
  layout: "default",
};
</script>

<style></style>
