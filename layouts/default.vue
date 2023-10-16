<template>
  <div>
    <Header />
    <main>
      <slot />
    </main>
    <Footer />
  </div>
</template>

<script scoped lang="ts">
  import Footer from '~/components/Footer.vue'
  import Header from '~/components/Header.vue'

  export default {
    name: 'default-layout',
    // eslint-disable-next-line vue/no-reserved-component-names
    components: { Footer, Header },
  }
</script>
