<template>
  <div>
    <NavbarComponent />
    <ContentComponent />
    <!-- <FooterComponent /> -->
    <!-- <ModalComponent /> -->
  </div>
</template>

<script setup>
  import 'flowbite/dist/flowbite'

  import NavbarComponent from './components/NavbarComponent.vue';
  import ContentComponent from './components/ContentComponent.vue';
  import FooterComponent from './components/FooterComponent.vue';
  // import ModalComponent from './components/ModalComponent.vue'


    // On page load or when changing themes, best to add inline in `head` to avoid FOUC
    //   if (localStorage.getItem('color-theme') === 'dark' || (!('color-theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
    //     document.documentElement.classList.add('dark');
    //      } else {
    //     document.documentElement.classList.remove('dark')
    // }
</script>