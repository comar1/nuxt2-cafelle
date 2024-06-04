<template>
  <div class="container">
    <h1>Hello, Nuxt with SASS!</h1>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style lang="scss" scoped>
@import '~/assets/styles.scss';

.container {
  text-align: center;
  padding: 20px;
}
</style>
