<template>
    <button class="button">{{ label }}</button>
</template>
<script>
export default {
  name: 'BaseButton',
  props: {
    label: String
  }
}
</script>
<style scoped>
.button {
  background-color: #3498db;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}
</style>
