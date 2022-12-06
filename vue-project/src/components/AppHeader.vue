<script setup>
defineProps({
  title: {
    type: String,
    default: "default Title",
  },
})
</script>

<template>
  <header>
    <h1><slot>{{ title }}</slot></h1>
  </header>
</template>

