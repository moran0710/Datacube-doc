<template>
  <div class="custom-layout">
    <Header />
    <main class="custom-main">
      <slot />
    </main>
    <Footer />
  </div>
</template>

<script setup>import Header from 'vuepress-theme-plume/components/VPDocHeader.vue'
import Footer from 'vuepress-theme-plume/components/VPFooter.vue'
</script>

<style scoped>.custom-layout {
  width: 100vw;
  margin: 0;
  padding: 0;
}

.custom-main {
  width: 100%;
  padding: 0;
}
</style>