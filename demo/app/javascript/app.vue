<template>
  <h1>{{ message }}</h1>
</template>

<script>
export default {
  data: function() {
    return {
      message: "I love Rails + Vue!"
    };
  }
};
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
