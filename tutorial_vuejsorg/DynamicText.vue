<script>
export default {
  data(){
    return {
      message: 'Make me dynamic'
    }
  }
}
</script>

<template>
  <h1>Make me dynamic!</h1>
  <h1>
    {{message.split('').reverse().join('')}}
  </h1>
  <h1>
    {{message.toUpperCase()}}
  </h1>
</template>