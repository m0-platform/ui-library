<script setup lang="ts">
defineProps<{
  size?: string | number;
  alt?: string;
}>();
</script>

<template>
  <img
    src="https://green-obedient-albatross-155.mypinata.cloud/ipfs/bafkreiatvb4wduh2ek5kdszcro264xbsmkk67pneksrry4b2jissljz3im"
    :width="size ?? 24"
    :height="size ?? 24"
    :alt="alt || 'Rise'"
    loading="lazy"
    decoding="async"
    referrerpolicy="no-referrer"
    class="rounded-full"
  />
</template>
