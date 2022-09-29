<template>
  <span className="user">
    <span className="name">{{ user.name }}</span>
    <span className="handle">{{ user.handle }}</span>
  </span>
</template>

<script setup>
defineProps({
  user: {
    type: Object,
    default: () => ({
      name: "Michael Jordan",
      handle: "@michaelJ",
    }),
  },
});
</script>
