<template>
  <header
    class="navbar bg-base-100 shadow-sm px-4 md:px-[150px] sticky top-0 left-0 z-40"
  >
    <div class="flex-1">
      <a class="btn btn-ghost text-xl">/maurice Mumbere ./</a>
    </div>
    <!-- Desktop Menu -->
    <div class="flex-none hidden md:block">
      <ul class="menu menu-horizontal px-1">
        <li>
          <nuxtLink to="#">Work</nuxtLink>
        </li>
        <li>
          <nuxtLink to="#">Skills</nuxtLink>
        </li>
        <li>
          <nuxtLink to="#">Contact</nuxtLink>
        </li>
      </ul>
    </div>
    <!-- Mobile Menu Button -->
    <div class="flex-none md:hidden">
      <button @click="isOpen = !isOpen" class="btn btn-ghost">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>
      </button>
    </div>
    <!-- Mobile Menu Dropdown -->
    <transition name="fade">
      <div
        v-if="isOpen"
        class="absolute top-full left-0 w-full bg-base-100 shadow-md md:hidden"
      >
        <ul class="menu menu-vertical px-4 py-2">
          <li>
            <nuxtLink to="#" @click="isOpen = false">Work</nuxtLink>
          </li>
          <li>
            <nuxtLink to="#" @click="isOpen = false">Skills</nuxtLink>
          </li>
          <li>
            <nuxtLink to="#" @click="isOpen = false">Contact</nuxtLink>
          </li>
        </ul>
      </div>
    </transition>
  </header>
</template>

<script setup>
import { ref } from "vue";
const isOpen = ref(false);
</script>

<style scoped>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.2s;
}
.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
</style>
