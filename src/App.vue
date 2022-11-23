<template>
  <div class="app__container">
    <HeaderComponent />
    <!-- <SwiperComponent /> -->
    <!-- <RegistrationComponent /> -->
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import RegistrationComponent from './components/RegistrationComponent.vue';
import SwiperComponent from './components/main-page/SwiperComponent.vue'
// import MainComponent from './components/main-page/MainComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    RegistrationComponent,
    SwiperComponent,
    // MainComponent
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
