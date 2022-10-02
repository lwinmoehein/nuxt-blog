<template>
  <div class="container mx-auto w-1/2 py-8">
    <h3 class="text-3xl font-bold">
      <NuxtLink
        :to="`/posts/1`"
        class="bg-blue-700 hover:bg-blue-800 text-white rounded inline-block px-4 py-2"
      >
        Title of the post
      </NuxtLink>
    </h3>
    <div class="post-meta text-gray-700 flex items-center space-x-2">
      <div>Feb 2 2022</div>
      <div>&middot;</div>
      <div>Lwin Moe Hein</div>
    </div>
    <div class="post-content mt-4">
      {{ $route.params.id }} Home Lorem ipsum dolor sit amet consectetur
      adipisicing elit. Esse reprehenderit quas, quae et nam ratione officia
      maxime vitae blanditiis minima, eum consectetur sint quia iste cum dicta,
      possimus aliquid dolorum!
    </div>
  </div>
</template>
