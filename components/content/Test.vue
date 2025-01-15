<script>
</script>

<template>
  <h2><ContentSlot :use="$slots.default" unwrap="p"/></h2>
  <div class="whatever">
    <ContentSlot :use="$slots.whatever" unwrap="p"/>
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