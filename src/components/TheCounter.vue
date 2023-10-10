<template>
  <h3>{{ counter }}</h3>
</template>

<script scoped>
export default {
  computed: {
    counter() {
      return this.$store.getters.finalCounter;
    },
  },
};
</script>
