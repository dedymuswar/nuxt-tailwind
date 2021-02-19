<template>
        <!-- NewsLetter -->
      <section>
        <div class="bg-gray-50 shadow-inner mb-8 flex py-10">
          <div
            class="flex flex-col w-full justify-center items-center space-y-6"
          >
            <h1
              class="text-2xl lg:text-3xl xl:text-3xl text-gray-600 subpixel-antialiased font-medium"
            >
              <span>Nuxt<span class="text-green-500 opacity-80">JS</span></span>
              NewsLetter
            </h1>
            <p class="text-gray-500 font-medium">
              Get the latest Nuxt news to your inbox, curated by the NuxtJS
              team.
            </p>

            <div class="relative">
              <form action="" method="post">
                <input
                  type="text"
                  name="email"
                  id=""
                  placeholder="Email"
                  class="px-6 py-3 border border-gray-200 rounded-lg w-96 focus:outline-none focus:border-green-500 overflow-hidden"
                />
                <button
                  type="button"
                  class="absolute right-0 text-white uppercase bg-emerald-400 hover:bg-emerald-300 px-6 py-3 rounded-r-lg border border-emerald-400 hover:border-emerald-300"
                >
                  Subscribe
                </button>
              </form>
            </div>
          </div>
        </div>
      </section>
</template>

<script>
export default {

}
</script>

<style>

</style>
