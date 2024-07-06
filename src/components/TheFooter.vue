<script setup>
import IconFooterLogo from "@/components/icons/IconFooterLogo.vue";
</script>

<template>
  <footer class="bg-[#2D223A]">
    <div class="container py-[47px] flex justify-between items-start">
      <a href="/" class="flex items-center">
        <icon-footer-logo />
        <h3
          class="text-[#00D1FF] text-[17px] leading-[17px] font-regular text-left"
        >
          Онлайн- <br />
          стенгазета
        </h3>
      </a>
      <div class="mt-5 flex flex-col items-end gap-4">
        <nav class="w-full max-w-[400px]">
          <ul class="flex flex-wrap justify-end gap-[14px]">
            <li>
              <a
                class="text-[17px] text-[#00D1FF] hover:text-white duration-200 font-regular leading-7"
                href="#"
                >Главная</a
              >
            </li>
            <li>
              <a
                class="text-[17px] text-[#FF2089] hover:text-white duration-200 font-regular leading-7"
                href="#"
                >Статьи</a
              >
            </li>
            <li>
              <a
                class="text-[17px] text-[#FFD52C] hover:text-white duration-200 font-regular leading-7"
                href="#"
                >Новости маркетинга</a
              >
            </li>
            <li>
              <a
                class="text-[17px] text-[#FB6614] hover:text-white duration-200 font-regular leading-7"
                href="#"
                >Популярное</a
              >
            </li>
            <li>
              <a
                class="text-[17px] text-[#7BFF00] hover:text-white duration-200 font-regular leading-7"
                href="#"
                >Создатели</a
              >
            </li>
          </ul>
        </nav>
        <p class="text-white leading-7 font-regular text-[15px] tracking-wider">
          Сайт был создан и наполнен волонтерской командой ADWAKE
        </p>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
</style>