<script setup>
import TheHeader from "@/components/TheHeader.vue";
import TheFooter from "@/components/TheFooter.vue";
import TheCommunity from "@/components/TheCommunity.vue";
</script>

<template>
  <the-header />
  <div class="main bg-[#9838F8]">
    <div class="container h-full">
      <div class="filter h-full pt-[20px]">
        <the-community />
      </div>
    </div>
  </div>
  <the-footer />
</template>

<style lang="scss" scoped>
</style>
