<script>
export default {
  mounted() {
    this.$refs.p.textContent = 'I have changed'
  }
}
</script>

<template>
  <p ref="p">hello</p>
</template>