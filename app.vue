<template>
  <div class="app">
    <CardContainer>
      Query params: {{ route.query }}
    </CardContainer>
  </div>
</template>

<script setup>
const route = useRoute()
</script>

<style>
.app {
  display: flex;
  justify-content: center;
}
</style>
