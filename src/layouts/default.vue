<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-3">
        <!-- 左侧菜单栏 -->
        <SidebarNav />
      </div>
      <div class="col-9">
        <div class="row">
          <div class="container-fluid">
            <!-- header nav -->
            <HeaderNav />
            <!-- main -->
            <router-view></router-view>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import SidebarNav from "@/components/SidebarNav.vue";
import HeaderNav from "@/components/HeaderNav.vue";
</script>

<style></style>
