<template>
  <div>
    <h1>Single User, ID: {{ $route.params.id }}</h1>
  </div>
</template>

<script>
export default {
  validate(data) {
    return /^\d+$/.test(data.params.id);
  }
};
</script>
