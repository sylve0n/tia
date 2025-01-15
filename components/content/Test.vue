<script>
</script>

<template>
  <h2><ContentSlot :use="$slots.heading" unwrap="p"/></h2>
  <div class="whatever"><ContentSlot :use="$slots.body"/></div>
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