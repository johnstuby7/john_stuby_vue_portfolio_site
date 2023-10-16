<script setup>
import { RouterLink, RouterView } from 'vue-router'
import FooterComponent from "../src/components/Footer_component.vue"
</script>

<template>
  <div id="app">
    <div id="nav">
      <nav>
        <RouterLink to="/">Home</RouterLink> &nbsp;
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>

    <RouterView />
  </div>
  <FooterComponent />
</template>