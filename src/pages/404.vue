<template>
  <div class="drama">
    <h1>404: This page doesn't exist.</h1>
    <p>Return <g-link to="/">home</g-link>.</p>
  </div>
</template>

<script>
export default {
  name: 'NotFound'
};
</script>

<style lang="scss" scoped>
.drama {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
a {
  display: inline-block;
  text-decoration: underline;
}
</style>
