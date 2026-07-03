<script setup lang="ts">
defineProps<{
  size?: string | number;
  alt?: string;
}>();
</script>

<template>
  <img
    src="https://green-obedient-albatross-155.mypinata.cloud/ipfs/bafkreiffdmhonsp3ouefx7ia56vetxh2ddy6dl3n2cg6377si2kvvzxq5u"
    :width="size ?? 24"
    :height="size ?? 24"
    :alt="alt || 'Monad'"
    class="rounded-full"
  />
</template>
