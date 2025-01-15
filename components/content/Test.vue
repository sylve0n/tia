<script>
</script>

<template>
  <h2><ContentSlot name="item"/></h2>
  <div class="whatever">
    <ContentSlot name="whatever"/>
  </div>
</template>

<style lang="scss" scoped>
  h2 {
    color: yellowgreen;
  }
  .whatever {
    color: white;
    background-color: indigo;
  }
</style>