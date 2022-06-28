<template>
  <div class="card">
    <h1>hello</h1>
    <component :is="clickable ? Cta : 'div'" label="ff" />
    <cta label="d"></cta>
    <fa-icon icon="fa-solid fa-user-secret" />
  </div>
</template>
<script setup>
import Cta from "unai-ui/components/elements/Cta";
const clickable = true;
</script>
