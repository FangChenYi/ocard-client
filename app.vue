<script setup lang="ts">
import './assets/styles/main.scss'
import HeaderComponents from './components/Header/HeaderComponents.vue';
</script>

<template>
  <div class="header-container">
    <div class="global-container">
      <header>
        <HeaderComponents />
      </header>
    </div>
  </div>
  <main></main>
</template>

<style lang="scss" scoped>
.global-container {
  width: 1200px;
  margin: auto;
}

.header-container {
  background-color: #ccc;
}
</style>