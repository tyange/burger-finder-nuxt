<template>
  <div>
    <Header/>
    <main>
      <slot/>
    </main>
  </div>
</template>
<script setup lang="ts">
import Header from "~/components/ui/header.vue";
</script>
