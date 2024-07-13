<template>
  <div class="bg-blue-950">
    <h1 class="bg-red-200">Hi</h1>
    {{ id }}
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style scoped></style>
