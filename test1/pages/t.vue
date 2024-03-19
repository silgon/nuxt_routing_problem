<script setup lang="ts">
 const route = useRoute()
 console.log(route.params)
</script>
<template>
  <h1>{{ route.params.a }}</h1>
  <nuxt-link :to="{params:{a:'hello'}}">hello</nuxt-link>
  <br/>
  <nuxt-link :to="{params:{a:'there'}}">there</nuxt-link>
</template>
