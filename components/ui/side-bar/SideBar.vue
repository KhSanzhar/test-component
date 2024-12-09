<script setup lang="ts">
const links = [
  {
    label: 'Dashboard',
    to: '/dashboard',
  },
  {
    label: 'Create',
    to: '/create',
  }
]
</script>
<template>
  <div class="absolute top-0 left-0 bg-gray-200 h-full w-1/12 flex justify-center items-center">
    <u-vertical-navigation :links="links" class="w-full"/>
  </div>
</template>