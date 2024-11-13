<template>
  <div class="bg-[#111827] min-h-screen">
     <NavBar />
</div> 
</template>

<script setup>
 import { defineAsyncComponent } from 'vue';
//Import Components Asynchronously
const NavBar = defineAsyncComponent(()=>import('@/components/NavBar.vue'));

</script>

<style>

*{
  scrollbar-width: thin;
  scrollbar-color: #111827 #f1f1f1;
}
</style>