<template>
  <h1 v-if="" @click="handler(arg, event)"></h1>
</template>

<script>
import { libName } from 'libName'

export default {
  props: {
    propName: {
      type: Number,
      default: 0
    }
  },
  data() {
    return {
      key: 'value'
    }
  },
}
</script>

<style></style>
