<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './header.vue';
import Menu from './menu.vue';
</script>

<template>
  <el-container class="layout_content">
    <el-header>
    <Header />
    </el-header>
    <el-container>
      <Menu />
      <el-main>
        <RouterView />
      </el-main>
    </el-container>
  </el-container>
</template>


<style lang="scss" scoped>
  .layout_content {
    width: 100%;
  }
</style>