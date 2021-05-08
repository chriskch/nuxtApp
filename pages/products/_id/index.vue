<template>
  <div>
    <h1>Product ID: {{ $route.params.id }}</h1>
    <nuxt-link to="/products">Back</nuxt-link>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>
