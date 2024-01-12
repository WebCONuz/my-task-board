<script lang="ts" setup>
useHead({ title: "Posts page" });
const route = useRoute();
</script>

<template>
  <h1>Post Page. Id: {{ route.params.id }}</h1>
</template>
