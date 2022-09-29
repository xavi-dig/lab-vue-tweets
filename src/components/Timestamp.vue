<template>
  <span class="timestamp">{{ timestamp }}</span>
</template>

<script setup>
defineProps({
  timestamp: {
    type: String,
    default: "Some random date", //- Podemos hacer string o función
    // default: () => {
    //   let date = new Date();
    //   return date.toISOString().split("T").[0];
    // },
  },
});
</script>
