<template>
  <div class="app__container">
    <HeaderComponent />
    <MainPageComponent />
    <!-- <RegistrationComponent /> -->
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import RegistrationComponent from './components/RegistrationComponent.vue';
import MainPageComponent from './components/MainPageComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    RegistrationComponent,
    MainPageComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background-color: #f1eeed;
}

.app__container {
  @apply flex justify-between flex-col gap-8 items-center
}
</style>
