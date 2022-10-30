<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Onemore from './components/Main/Onemore.vue'
import Chat from './components/Main/Chat.vue'
</script>

<template>
  <header>

    <div class="wrapper">
      <nav class="flex">
        <Header />
        <Onemore />
        <Chat />
        <!-- <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink> -->
      </nav>
    </div>
  </header>

  <RouterView />
</template>