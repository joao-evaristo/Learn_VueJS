<script>
export default {
  emits: ['response', 'response2'],
  created() {
    this.$emit('response', 'hello from child')
    this.$emit('response2', 'other message')
  }
}
</script>

<template>
  <h2>Child component</h2>
</template>