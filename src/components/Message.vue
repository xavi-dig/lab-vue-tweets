<template>
  <p className="message">
    {{ message }}
  </p>
</template>

<script setup>
defineProps({
  message: {
    type: String,
    default: "Some generic tweet about a dog",
  },
});
</script>
