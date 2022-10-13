<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      this.count ++
    },
    decrement() {
			this.count --  
		}
  }
} 
</script>

<template>
  <!-- make this button work -->
  <button @click='increment'>increment</button> <!-- v-on:event = @event -->
  <br>
  <button @click='decrement'>decrement</button>
  <p>
    Count is: {{count}}
  </p>
</template>