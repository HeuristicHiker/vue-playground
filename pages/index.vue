<template>
  <div>Hello from main page</div>
</template>

<script setup>
useSeoMeta({
  title: "Amazing Site",
  ogTitle: "Amazing Site",
  ogDescription: "Some description",
  ogImage: "[og:image]",
  ogUrl: "[og:url]",
  twitterTitle: "Main Page",
  twitterDescription: "[twitter:description]",
  twitterImage: "[twitter:image]",
  twitterCard: "summary",
  description: "Some description",
});
</script>
