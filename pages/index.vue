<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <div>
    <h1>Nuxt Routing set up successfully!</h1>
    <p>Current route: {{ route.path }}</p>
    <p>
      
<NuxtLink to="/api/login" external>
	Sign in
</NuxtLink>
<NuxtLink to="/api/register" external>
	Sign up
</NuxtLink>
    </p>
    
    <a href="https://nuxt.com/docs/getting-started/routing" class="underline text-blue-200" target="_blank">Learn more about Nuxt Routing</a>
  </div>
</template>
