<template>
  <div class="hero-simple-centered">
    <div
      class="mt-10 mx-auto max-w-screen-xl px-4 sm:mt-12 sm:px-6 md:mt-10 lg:mt-14 xl:mt-18"
    >
      <div class="text-center">
        <h2
          class="text-2xl font-extrabold md:text-4xl"
        >
          Recent Projects
        </h2>
  <div class="p-10 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-5">
    <!--Card 1-->
    <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl transition duration-500 ease-in-out rounded-md">
      <div class="px-6 pt-4 pb-2">
        <div class="font-bold text-xl mb-2">proximity-hill</div>
        <p class="text-gray-700 text-base">
          A node-hill script that integrates PeerJS voice chat with proximity volume. Expirementing with sockets and math!
        </p>
      </div>
      <div class="px-6 pt-2 pb-4">
          <a href="https://github.com/dragonismcode/proximity-hill"><CodeIcon class="inline-block h-5 w-5 mx-2"/></a>
          <a href="https://www.brick-hill.com/play/30492"><PlayIcon class="inline-block h-5 w-5 mx-2 "/></a>
      </div>
    </div>
    <!--Card 2-->
    <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl transition duration-500 ease-in-out rounded-md">
      <div class="px-6 pt-4 pb-2">
        <div class="font-bold text-xl mb-2">dragonism.tech</div>
        <p class="text-gray-700 text-base">
          My personal website to show off my skills and projects. Displays my socials and where to find and contact me.
        </p>
      </div>
      <div class="px-6 pt-2 pb-4">
          <a href="https://github.com/dragonismcode/dragonism.tech"><CodeIcon class="inline-block h-5 w-5 mx-2 "/></a>
          <a href="https://dragonism.tech"><GlobeAltIcon class="inline-block h-5 w-5 mx-2 "/></a>
      </div>
    </div>

    <!--Card 3-->
    <div class="rounded overflow-hidden shadow-lg hover:shadow-2xl transition duration-500 ease-in-outrounded-md">
      <div class="px-6 pt-4 pb-2">
        <div class="font-bold text-xl mb-2">BenBot</div>
        <p class="text-gray-700 text-base">
          BenBot is a random/fun bot for DogeHouse. With a variety of commands, it brings fun to every DogeHouse room.
        </p>
      </div>
      <div class="px-6 pt-2 pb-4">
          <a href="https://github.com/dragonismcode/benbot"><CodeIcon class="inline-block h-5 w-5 mx-2 "/></a>
      </div>
    </div>
  </div>
</div>
</div>
</div>
</template>

<script>
import { GlobeAltIcon, CodeIcon, PlayIcon } from '@heroicons/vue/solid'

export default {
  components: { GlobeAltIcon, CodeIcon, PlayIcon }
}
</script>