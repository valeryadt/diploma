<template>
  <div class="app__container">
    <HeaderComponent />
    <MainComponent />
    <!-- <RegistrationComponent /> -->
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import RegistrationComponent from './components/RegistrationComponent.vue';
import MainComponent from './components/main-page/MainComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    RegistrationComponent,
    MainComponent
  }
}
</script>

<style>
#app {
  background-color: #f1eeed;
}

.app__container {
  @apply flex justify-between flex-col items-center
}
</style>
