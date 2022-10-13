<script>
import ChildComp from './ChildComp.vue'

export default {
  components: {
    ChildComp
  },
  data() {
    return {
      greeting: ''
    }
  },
  methods: {
    sendHello(){
      this.greeting = 'Hello from parent'
    }
  }
}
</script>

<template>
  <ChildComp :msg='greeting'/>
  <button @click='sendHello'>Send message</button>
</template>