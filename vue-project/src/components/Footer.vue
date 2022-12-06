<script setup>
defineProps({
  title: {
    type: String,
    default: "footer",
  },
})
</script>

<template>
  <footer><slot>{{title}}</slot></footer>
</template>