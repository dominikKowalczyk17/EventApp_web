<script setup>
import { FwbNavbar, FwbNavbarCollapse, FwbNavbarLink } from "flowbite-vue";
</script>

<template>
  <fwb-navbar>
    <template #logo>
      <fwb-navbar-title
        alt="Flowbite logo"
        class="font-sans font-bold text-xl text-white"
        link="#"
      >
        Event Managment
      </fwb-navbar-title>
    </template>
    <template #default="{ isShowMenu }">
      <fwb-navbar-collapse :is-show-menu="isShowMenu">
        <fwb-navbar-link is-active link="#"> Home</fwb-navbar-link>
        <fwb-navbar-link link="#"> Events</fwb-navbar-link>
        <fwb-navbar-link link="#"> About</fwb-navbar-link>
        <fwb-navbar-link link="#"> Contact</fwb-navbar-link>
      </fwb-navbar-collapse>
    </template>
  </fwb-navbar>
</template>