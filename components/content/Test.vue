<script setup>
  defineProps({
    href: {
      type: String,
      required: true,
    },
    external: {
      type: Boolean,
      default: false,
    },
    icon: {
      type: String,
      default: '',
    },
  })
</script>

<template>
  <h2><ContentSlot :use="$slots.default" unwrap="p"/></h2>
  <div class="whatever"><ContentSlot name="whatever"/></div>
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