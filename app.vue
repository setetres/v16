<script setup lang="ts">
  const route = useRoute()
</script>
<template>
  <App>
    <NuxtLoadingIndicator color="#f59e0b" />
    <Header />
    <Content>
      <NuxtPage />
    </Content>
    <div class="flex flex-col flex-1 bg-emerald-200">
      <div class="flex flex-row flex-1">
        <Navigation />
      </div>
      <Footer />
    </div>
  </App>
</template>
