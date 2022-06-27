<template>
  <footer>
    <Strong>{{ footerText }}</Strong>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      footerText: 'Copyright 2022',
    };
  },
};
</script>

<style scoped>
  footer {
    background-color:azure;
    padding: 10px;
  }
</style>
