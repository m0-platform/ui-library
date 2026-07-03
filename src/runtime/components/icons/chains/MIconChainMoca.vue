<script setup lang="ts">
defineProps<{
  size?: string | number;
  alt?: string;
}>();
</script>

<template>
  <img
    src="https://green-obedient-albatross-155.mypinata.cloud/ipfs/bafkreibcsv2y4pz7sibazq6ibtta2teqtiu4anvfabgdxm3h3sbw5g74dy"
    :width="size ?? 24"
    :height="size ?? 24"
    :alt="alt || 'Soneium'"
    class="rounded-full"
    loading="lazy"
    decoding="async"
    referrerpolicy="no-referrer"
  />
</template>
