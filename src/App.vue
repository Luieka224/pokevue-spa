<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
import NavBar from '@/components/nav/NavBar.vue'
</script>

<template>
  <NavBar />
  <div class="flex space-x-4">
    <router-link to="Home" class="rounded bg-green">Go to Home</router-link>
    <router-link to="About" class="rounded bg-green">Go to About</router-link>
  </div>
  <router-view />
</template>