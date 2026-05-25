<script setup lang="ts">
import { useRoute, type RouteLocationNormalizedLoaded } from 'vue-router'

const route = useRoute() as RouteLocationNormalizedLoaded & {
  params: {
    id?: string
  }
}
</script>

<template>
  <div>
    <h1>Projects {{ route.params.id }}</h1>
  </div>
</template>

<style lang="">

</style>
google-chrome --ozone-platform=x11
