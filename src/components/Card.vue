<template>
  <div>
    <h1>{{ test }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    heading: {
      type: String,
      default: "test",
      required: true
    }
  }
};
</script>

<style>
</style>