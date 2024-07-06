<script setup>
import IconLogo from "@/components/icons/IconLogo.vue";
</script>

<template>
  <header class="header bg-[#6F0DEE]">
    <div class="container py-[7px] flex items-center justify-between">
      <a href="/" class="inline-block w-[78px]">
        <icon-logo />
      </a>
      <nav>
        <ul class="flex items-center gap-16">
          <li>
            <a
              class="text-white text-[17px] hover:text-[#00D1FF] duration-200 font-medium leading-[22px]"
              href="#"
              >Главная</a
            >
          </li>
          <li>
            <a
              class="text-white text-[17px] hover:text-[#FB6614] duration-200 font-medium leading-[22px]"
              href="#"
              >Популярное</a
            >
          </li>
          <li>
            <a
              class="text-white text-[17px] hover:text-[#FFD52C] duration-200 font-medium leading-[22px]"
              href="#"
              >Новости маркетинга</a
            >
          </li>
          <li>
            <a
              class="text-white text-[17px] hover:text-[#FF2089] duration-200 font-medium leading-[22px]"
              href="#"
              >Статьи</a
            >
          </li>
          <li>
            <a
              class="text-white text-[17px] hover:text-[#7BFF00] duration-200 font-medium leading-[22px]"
              href="#"
              >Создатели</a
            >
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
</style>