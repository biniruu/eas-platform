<template>
  <header>
    <nav role="list">
      <span role="listitem"><NuxtLink to="/">Index</NuxtLink></span>
      <span role="listitem"><NuxtLink to="/about">About</NuxtLink></span>
      <span role="listitem"><NuxtLink to="/contact">Contact</NuxtLink></span>
    </nav>
  </header>
</template>

<script scoped lang="ts">
  export default {
    name: 'header-comp',
  }
</script>
