<script setup lang="ts">
defineProps<{
  size?: string | number;
  alt?: string;
}>();
</script>

<template>
  <img
    src="https://green-obedient-albatross-155.mypinata.cloud/ipfs/bafkreidw7akutkkrhmywnynoi736mirnbi34uhq577r5hsumz2psfqyfye"
    :width="size ?? 24"
    :height="size ?? 24"
    :alt="alt || 'Soneium'"
    class="rounded-full"
    loading="lazy"
    decoding="async"
    referrerpolicy="no-referrer"
  />
</template>
