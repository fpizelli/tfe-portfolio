<template>
<div class="flex flex-col min-h-screen">
  <NavbarComponent/>
  <div class="main flex-grow">
    <router-view></router-view>
  </div>
  <FooterComponent/>
</div>
</template>

<script setup>
import NavbarComponent from './components/NavbarComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
</script>