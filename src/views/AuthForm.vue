<template>
  <form action="" @submit="onClick">
    <input
      type="text"
      required
      pattern="^(?=.*[A-Za-z])(?=.*\d)[A-Za-z\d]{8,}$"
    />
  </form>
</template>
<script>
export default {
  methods: {
    onClick() {
      console.log("Clicked");
    },
  },
};
</script>
<style scoped>
</style>