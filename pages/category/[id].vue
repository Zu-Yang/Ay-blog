<template>
  <div>分类{{ route.params.id }}</div>
</template>

<script setup lang="ts">
const route = useRoute();

// 当访问/posts/1时，route.params.id将为1
console.log(route.params.id);

definePageMeta({
  title: "分类",
});
</script>
