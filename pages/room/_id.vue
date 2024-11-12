<script setup>
const router = useRouter();
const route = useRoute();
</script>

<template>
  <h2>房型詳細頁面 {{ route.fullPath }}</h2>
  <button @click="router.go(-1)">前往上一頁</button>
</template>

<style scoped></style>
