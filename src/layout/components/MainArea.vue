<script setup>
</script>

<template>
  <div class="main-area">
    <RouterView v-slot="{ Component }">
      <transition name="fade">
        <component :is="Component"></component>
      </transition>
    </RouterView>
  </div>
</template>

<style scoped lang="less"></style>
