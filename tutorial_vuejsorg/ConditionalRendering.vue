<script>
export default {
  data() {
    return {
      awesome: true
    }
  },
  methods: {
    toggle() {
      this.awesome = !this.awesome ? true : false
    }
  }
}
</script>

<template>
  <button @click="toggle">toggle</button>
  <h1 v-if='awesome'>Vue is awesome! 😍</h1>
  <h1 v-else='awesome'>Oh no 😢</h1>
</template>