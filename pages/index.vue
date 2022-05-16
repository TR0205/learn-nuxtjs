<template>
  <div>
    index<br>
    <!-- router-linkっぽいの -->
    <NuxtLink to="/about">about</NuxtLink>
    <NuxtLogo />
    <BaseHeader />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
