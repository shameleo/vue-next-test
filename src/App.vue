<template>
  <div>{{ notexists }}</div>
</template>

<script lang="ts">
import { ref } from 'vue'

export default {
  setup() {
    const test = ref(0)

    return {
      test
    }
  }
}
</script>
