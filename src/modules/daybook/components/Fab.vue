<template>
  <button class="btn btn-primary">
    <i class="fa fa-2x" :class="props.icon ?? 'fa-plus'"></i>
  </button>
</template>

<script setup>
import { defineProps } from 'vue'

const props = defineProps(['icon'])

console.log(props)
</script>

<style lang="scss" scoped>
button {
  position: fixed;
  bottom: 10px;
  right: 10px;
  width: 80px;
  height: 80px;
  border-radius: 80%;
}
</style>
