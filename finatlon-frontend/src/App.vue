<template>
    <header-component />
    <div class="main">
        <main-view />
    </div>
    <footer-component />
</template>

<script>
import FooterComponent from './components/footerComponent/FooterComponent.vue';
import HeaderComponent from './components/headerComponent/HeaderComponent.vue';
import MainView from './views/mainView/MainView.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent, MainView, FooterComponent
  }
}
</script>

<style>
.main {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  background-color: #ffffff;
  background: url('./assets/bg-ornament.png'), linear-gradient(180deg, rgba(254,244,238,0.15) 0%, rgba(245,121,81,0.15) 100%);
  background-repeat: repeat;
  background-size: 20%;
}
</style>
