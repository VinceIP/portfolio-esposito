<script setup>
import { RouterLink, RouterView } from "vue-router";
import NavComponent from "./components/NavComponent.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <NavComponent />
      </nav>
    </div>
  </header>
  <RouterView />
</template>

<style scoped>
.wrapper{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}
</style>
