<script setup lang="ts">
import { createVNode, RenderFunction } from 'vue'

const HelloWorld: RenderFunction = () => {
  return createVNode('h1', {}, 'Hello world')
}
</script>

<template>
  <HelloWorld />
</template>
