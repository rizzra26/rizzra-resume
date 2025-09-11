<script setup lang="ts">
useHead({
  title: ref("Rizky R. | Resume"),
  meta: [
    {
      name: "description",
      content: "Rizky's Resume",
    },
  ],
});
</script>

<template>
  <div
    class="flex flex-col overflow-hidden lg:flex-row bg-[url(/images/left-bg.jpg)]"
  >
    <NuxtPage />
  </div>
</template>
