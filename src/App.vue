<script setup lang="ts">
</script>

<template>
  <!-- <metainfo></metainfo> -->

  <router-view v-slot="{ Component }">
    <keep-alive>
      <component :is="Component" />
    </keep-alive>
  </router-view>
</template>

<style>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
#nprogress .bar {
  background-color: aquamarine !important;
}
.markdown-body img {
    opacity: 0.5;
    border: 1px gray dotted !important;
}
.markdown-body img:hover {
    opacity: 1;
}
</style>