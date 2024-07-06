<script setup>
import IconButton from "@/components/icons/IconButton.vue";
import personOne from "@/assets/images/team/person1.jpg";
</script>

<template>
  <button class="ml-4 flex flex-col items-end gap-2 w-max">
    <IconButton />
    <span class="font-bold text-xs leading-[14px]">назад</span>
  </button>
  <h1
    class="uppercase mt-4 text-[#9747FF] text-[56px] leading-[59px] text-center"
  >
    наша команда
  </h1>
  <div class="w-full mt-4 px-4">
    <div class="w-full max-w-[740px] m-auto">
      <div class="w-full">
        <div>
          <img :src="personOne" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
</style>