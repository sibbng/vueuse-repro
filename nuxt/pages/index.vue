<template>
  <div>
    {{x}} {{y}}
  </div>
</template>

<script lang="ts">
import { useMouse } from '@vueuse/core'

export default {
  setup() {
    const { x, y } = useMouse()

    return { x, y }
  }
}
</script>