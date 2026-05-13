<script setup lang="ts">
defineProps<{
  size?: string | number;
  alt?: string;
}>();
</script>

<template>
  <img
    src="https://green-obedient-albatross-155.mypinata.cloud/ipfs/bafkreiam5jndlyhh4owaktg56wofifdmm5x5v7kdvsndgjzoidzyzocskq"
    :width="size ?? 24"
    :height="size ?? 24"
    :alt="alt || 'Soneium'"
    class="rounded-full"
  />
</template>
