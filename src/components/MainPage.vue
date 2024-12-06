<script setup>

import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
import Events from "@/components/Events.vue";
</script>

<template class="flex flex-col min-h-screen">
  <Navbar class="flex-shrink-0"/>
      <Events/>
  <Footer class="flex-shrink-0"/>
</template>