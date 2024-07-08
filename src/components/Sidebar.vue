<template>
    <el-menu default-active="1" class="el-menu-vertical-demo">
      <el-submenu index="1">
        <template #title>
          <i class="el-icon-location"></i>
          <span>Dashboard</span>
        </template>
        <el-menu-item-group>
          <el-menu-item index="/dashboard/overview">Overview</el-menu-item>
          <el-menu-item index="/dashboard/reports">Reports</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
    </el-menu>
  </template>
  
  <script setup lang="ts">
  import { defineComponent } from 'vue'
  </script>
  
  <style scoped lang="scss">
  // Adjust styles as needed
  </style>