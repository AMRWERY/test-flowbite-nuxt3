<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtLoadingIndicator />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup>
// initialize components based on data attribute selectors
onMounted(() => {
  useFlowbite(() => {
    initFlowbite();
  })
})
</script>