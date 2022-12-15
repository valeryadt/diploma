<template>

  <div class="header">
    <div class="header__panel">
      <div class="header__catalog">
        <div class="header__panel-item">
          <Slide :isOpen="isOpen" @closeMenu="isOpen = false" :burgerIcon="false">
            <a id="home" href="#">
              <div class=" menu__list">
                <span class="menu__list-item">Сухие смеси и грунтовки</span>
                <span class="menu__list-item">Металлопрокат</span>
                <span class="menu__list-item">Гидроизоляция</span>
                <span class="menu__list-item">Теплоизоляция</span>
                <span class="menu__list-item">Мембраны, геотекстиль</span>
                <span class="menu__list-item">Стеновые материалы</span>
                <span class="menu__list-item">Расходные материалы</span>
              </div>
            </a>
          </Slide>
          <div @click="isOpen = true">Каталог</div>
        </div>
      </div>
      <div class="header__panel-list">
        <div class="header__panel-item"><a href="#about">О нас</a></div>
        <div class="header__panel-item">Доставка</div>
        <div class="header__panel-item">Оплата</div>
        <div class="header__panel-item">Возврат</div>
      </div>
      <div class="header__registration">
        <div class="header__panel-item">
          Вход/Регистрация
        </div>
      </div>
    </div>
  </div>
  <div>
  </div>
</template>

<script lang="js">
import { Slide } from 'vue3-burger-menu'

export default {
  name: "HeaderComponent.vue",
  data() {
    return { isOpen: false }
  },
  components: {
    Slide
  },
  mounted() {

  }
}
</script>

<style scoped>
.header {
  @apply w-full h-12 flex items-center gap-2
}

.header__catalog {
  @apply flex justify-start items-center
}

.header__panel {
  @apply flex flex-row text-gray-300 w-full pl-10 pr-10 justify-between
}

.header__panel-item {
  @apply cursor-pointer hover: (text-light-200)
}

.header__panel-list {
  @apply flex flex-row gap-4
}

.menu__list {
  @apply flex flex-col text-gray-300 gap-4
}

.menu__list-item {
  @apply border border-l-0 border-r-0 border-t-0 border-b-gray-500 hover: (text-white)
}

.header {
  background-color: #3a3a82
}

.bm-menu {
  background-color: rgb(27, 27, 175);
}
</style>