<template>
  <div>
    <my-header />
    <nuxt />
    <my-footer />
  </div>
</template>

<script>
import MyHeader from '~/components/Header.vue'
import MyFooter from '~/components/Footer.vue'
export default {
  name: 'navbar',
  components: {
    MyHeader,
    MyFooter
  }
}
</script>

<style lang="scss" scoped>
*,
*:before,
*:after {
  margin: 0;
}
</style>
