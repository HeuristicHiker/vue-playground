<template>
  <div class="container mx-auto max-w-2xl">
    <header class="flex justify-between items-center">
      <div>
        <NuxtLink to="/" class="text-xl font-semibold p-2 hover:bg-gray-200"
          >Connor</NuxtLink
        >
      </div>
      <Menu />
    </header>
    <main class="p-2 m-10">
      <slot />
    </main>
  </div>
</template>

<script setup>
useHead({
  titleTemplate: "%s - Connor",
  link: [
    {
      rel: "preconnect",
      href: "https://fonts.googleapis.com",
    },
    {
      rel: "stylesheet",
      href: "https://fonts.googleapis.com/css2?family=Roboto&display=swap",
      crossorigin: "",
    },
  ],
});
</script>

<style>
body {
  font-family: "Roboto";
}
</style>
