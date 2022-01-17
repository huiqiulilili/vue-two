<template>
  <div class="category">
    <h3>XXX分类</h3>
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "Category"
}
</script>

<style scoped>
.category{
  background-color: aqua;
  width: 200px;
  height: 300px;
}
h3{
  text-align: center;
  background-color: orange;
}
</style>
