<template>
  <li>{{ name }}, {{ number }}</li>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      required: true
    },
    number: {
      type: Number,
      required: true
    }
  }
}
</script>
