<template>
  <div class="section is-large">
    <the-nav :links="links"></the-nav>
    <slot />
  </div>
</template>

<script setup lang="ts">
import TheNav from "unai-ui/components/patterns/TheNav";
const links = [
  { title: "Home", link: "/" },
  { title: "Logo", link: "/", type: "img", src: "/logo.png" },
  { title: "Contact", link: "/contact" },
];
</script>
<style>
body {
  background-color: rgba(0, 30, 38);
}
</style>
